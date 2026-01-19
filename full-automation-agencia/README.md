# Full Automation Agency Stack

Esta é uma infraestrutura completa para **agências de automação e SaaS**. Ela consolida múltiplas ferramentas open-source em um único servidor, permitindo oferecer serviços de chatbots, atendimento e armazenamento para clientes.

## 🛠️ Ferramentas Inclusas
* **Typebot:** Construtor visual de chatbots avançados.
* **Chatwoot:** Central de atendimento omnichannel (WhatsApp, Site, Instagram).
* **MinIO:** Armazenamento de arquivos compatível com S3 (para salvar mídias dos bots).
* **Uptime Kuma:** Monitoramento de status dos serviços.
* **PostgreSQL + Redis:** Camada de dados robusta compartilhada.

## 🚀 Diferenciais
* **Integração Nativa:** O Typebot já está configurado para salvar arquivos no MinIO e logs no Postgres.
* **Custo-Eficiente:** Toda a stack roda em um único servidor parrudo (ex: Hetzner/Contabo) via Docker.
