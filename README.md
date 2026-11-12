# 🏗️ Cotação Regional & HelpDesk JRS

Repositório com dois projetos independentes desenvolvidos para fins de estudo e prática de desenvolvimento web e APIs REST:

1. **`api-cotacoes`**: Aplicação full-stack para consulta de materiais de construção, pontos de venda regionais e solicitação de cotações.
2. **`helpdesk-jrs`**: API REST local para simulação de sistema de chamados utilizando JSON REST Server (JRS).

---

## 📦 1. `api-cotacoes` — Catálogo e Solicitação de Cotações

Aplicação web completa onde clientes podem se cadastrar, navegar pelo catálogo de materiais de construção (com busca e filtros por categoria/preço), visualizar pontos de venda regionais e montar um carrinho para solicitar cotações.

### 🛠️ Tecnologias Utilizadas
* **Front-end:** React + Vite
* **Back-end (API):** Node.js, Express e TypeScript
* **Banco de Dados:** PostgreSQL com Prisma ORM

### 📋 Pré-requisitos
* [Node.js](https://nodejs.org/) e `npm` instalados
* Instância do [PostgreSQL](https://www.postgresql.org/) em execução

### 🚀 Como Executar

> **Importante:** O front-end consome a API. Portanto, execute o back-end e o front-end em **dois terminais separados**.

#### Passo 1: Configurar e iniciar a API
No terminal (PowerShell), a partir da raiz do repositório:

```powershell
cd api-cotacoes
npm install
Copy-Item .env.example .env
