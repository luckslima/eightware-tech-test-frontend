# Frontend - Eightware Tech Test

Este é o frontend da aplicação desenvolvida para o teste técnico da Eightware. Ele foi construído com **Next.js 15** e utiliza **API Routes** para intermediar as requisições ao backend.

---

## 🚀 Como rodar o projeto

### 1️⃣ Pré-requisitos

- **Node.js**: versão 18 ou superior
- **npm**: versão 8 ou superior

### 2️⃣ Configuração do ambiente

1. Clone o repositório:
   ```bash
   git clone https://github.com/luckslima/eightware-tech-test-frontend.git
   cd frontend

2. Instale as dependências:
   ```bash
   npm install

3. Inicie o servidor:
   ```bash
   npm run dev

obs: O frontend estará disponível em: http://localhost:3000

## 🧪 Como rodar os testes

1. Execute os testes com o Jest:
   ```bash
   npm test

2. Cobertura dos testes:

- Testes do formulário de criação de conta (/signup).
- Testes do formulário de login (/login).
- Testes da página protegida de perfil (/profile).

## 📚 Páginas disponíveis

### /signup

- Formulário para criação de conta.

### /login

- Formulário para login.

### /profile

- Página protegida que exibe os dados do usuário logado.
- Requer autenticação via JWT.

## 🛠️ Tecnologias utilizadas

- Next.js 15
- Jest + Testing Library
- API Routes

## 📄 Licença

Este projeto é apenas para fins de avaliação técnica.