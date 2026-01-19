# 🐳 Docker Compose Stacks

Coleção de infraestruturas Docker prontas para produção, focadas em **alta performance**, **escalabilidade** e **segurança**.

## 📂 O que você vai encontrar aqui:

| Stack | Perfil | Tecnologias Principais |
| :--- | :--- | :--- |
| **[🏢 N8N Enterprise Scale](./n8n-enterprise-scale)** | Alta Carga | **N8N** (Queue Mode) + **Redis** + **Postgres** (Tuned) |
| **[🚀 Full Automation Agency](./full-automation-agencia)** | Agência/SaaS | **Typebot** + **Chatwoot** + **MinIO** + **N8N** + **Evolution API** |
| **[🛡️ Proxy Manager](./proxy-manager)** | Segurança | **Nginx** (WAF) + **Caddy** (SSL Automático) |

## ⚙️ Como usar

1. Clone este repositório.
2. Entre na pasta da stack desejada (ex: `cd n8n-enterprise-scale`).
3. Copie o arquivo de exemplo de variáveis: `cp ../.env.example .env`
4. Ajuste suas credenciais no `.env`.
5. Suba a stack: `docker compose up -d`

## 🔒 Segurança

Todas as credenciais sensíveis foram removidas e substituídas por variáveis de ambiente.
