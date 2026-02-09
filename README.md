# 🚀 Game Store Backend API

Backend da API RESTful para uma **Loja de Games**, responsável por gerenciar os dados de **Produtos (Jogos)** e suas respectivas **Categorias**.

O projeto foi desenvolvido utilizando **NestJS**, um framework progressivo para Node.js, garantindo organização modular, escalabilidade e boas práticas de arquitetura backend.

---

## 🛠️ Tecnologias Utilizadas

- **Framework:** NestJS  
- **Linguagem:** TypeScript  
- **Banco de Dados:** MySQL  
- **ORM:** TypeORM  
- **Runtime:** Node.js  
- **Gerenciador de Pacotes:** npm  

---

## 📌 Funcionalidades

- ✅ CRUD completo de Jogos (Produtos)  
- ✅ CRUD completo de Categorias  
- ✅ Relacionamento entre Jogos e Categorias  
- ✅ Validação de dados com DTOs  
- ✅ Tratamento de exceções  
- ✅ Estrutura modular com NestJS  

---

## 🧠 Conceitos Aplicados

- Arquitetura modular  
- Injeção de dependência  
- Padrão REST  
- Relacionamentos com TypeORM  
- Boas práticas de organização de código  
- Separação de responsabilidades (Controller, Service, Module)

---

## 📂 Estrutura do Projeto

```bash
src/
├── produto/
├── categoria/
├── app.module.ts
└── main.ts
```

# ⚙️ Como Executar o Projeto

1️⃣ Clonar o repositório
```
git clone https://github.com/seu-usuario/game-store-backend.git
```

2️⃣ Instalar dependências
```
npm install
```

3️⃣ Configurar o banco de dados

Crie um arquivo .env na raiz do projeto com suas configurações:
```
DB_HOST=localhost
DB_PORT=3306
DB_USERNAME=root
DB_PASSWORD=sua_senha
DB_DATABASE=game_store
PORT=3000
```

4️⃣ Executar a aplicação
```
npm run start:dev
```

A API estará disponível em:
```
http://localhost:3000
```

# 📌 Status do Projeto

🚧 Projeto acadêmico desenvolvido para prática de construção de API REST com NestJS e integração com banco de dados relacional.

👩‍💻 Desenvolvedora

Gabrieli Martins
Estudante de Análise e Desenvolvimento de Sistemas 💻

LinkedIn: [Se conecte comigo!](https://linkedin.com/in/gabrielimartinsdev)
