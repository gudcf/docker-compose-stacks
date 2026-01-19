# N8N Enterprise Scale Stack

Esta stack é configurada para **alta performance e escalabilidade**. Diferente de instalações comuns, esta arquitetura separa a interface principal (Main) dos processadores de execução (Workers) usando Redis como fila.

## Destaques Técnicos
* **PostgreSQL Tuning:** Configurações personalizadas para lidar com alto volume de escritas (`max_connections=500`, `shared_buffers=512MB`).
* **Queue Mode:** Utiliza Redis para gerenciar a fila de execução, garantindo que o editor não trave durante picos de carga.
* **Horizontal Scaling:** Configurado para rodar múltiplos workers simultaneamente.

## Como rodar
1. Copie o `.env.example` para `.env`
2. `docker compose up -d`
