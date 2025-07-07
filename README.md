# Ateliê Fio & Alma

Este repositório contém o projeto **"Ateliê Fio & Alma"**, uma plataforma colaborativa que conecta criadores de moda personalizada a clientes em busca de peças exclusivas. Nosso objetivo é ser a ponte entre quem busca confecções únicas e artistas que transformam ideias em realidade, com foco em roupas personalizadas.

## Visão Geral

O Ateliê Fio & Alma funciona como um e-commerce de exposição onde:
* **Clientes** podem visualizar peças e expressar interesse via formulários.
* **Criadores** gerenciam suas vitrines de peças personalizadas após aprovação.
* **Administradores** controlam aplicações de criadores, usuários e produtos da plataforma.

## Tecnologias Utilizadas

* **Frontend:** React.js, HTML, CSS, JavaScript
* **Backend:** Node.js, Express.js
* **Banco de Dados:** MongoDB (NoSQL)
* **Outras:** Mongoose, Multer (upload de imagens), Nodemailer (envio de e-mails)

## Como Rodar Localmente

Siga os passos abaixo para configurar e executar o projeto em sua máquina.

### Pré-requisitos
* Node.js (v14+)
* npm
* MongoDB (local ou Atlas)
* Conta Gmail (para Nodemailer)

### 1. Configuração do Backend
```bash
git clone <URL_DO_SEU_REPOSITORIO>
cd fio-e-alma/backend
npm install
# Crie o arquivo .env (MONGO_URI, JWT_SECRET, EMAIL_USER, EMAIL_PASS)
npm run dev
