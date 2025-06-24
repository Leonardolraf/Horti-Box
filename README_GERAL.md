# Projeto HortiBox

O **HortiBox** é uma aplicação web para gerenciamento de vendas e estoque de hortifrúti. Inclui uma API completa com autenticação e um frontend moderno para uso administrativo.

## 👥 Integrantes

- Leonardo Rodrigues Amorim Filho - UC23101012
- Matheus Figueredo Da Silva - UC23100843
- Mario Eduardo Pereira De Sousa - UC23101279

## 🗂️ Estrutura

- `/hortibox-backend`: API REST em NestJS
- `/hortibox-frontend`: Interface web em React + Vite

## 🚀 Como executar o projeto

### Backend

```bash
cd hortibox-backend
npm install
# Configure o arquivo .env com dados do banco
npm run start:dev
```

Acesse a API em:

```
http://localhost:3000
```

### Frontend

```bash
cd hortibox-frontend
npm install
npm run dev
```

Acesse a interface:

```
http://localhost:5173
```

## ✅ Pré-requisitos

- Node.js 18+
- PostgreSQL rodando localmente (ou serviço em nuvem)
