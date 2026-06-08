# 🏡 Mandattum

## Sobre o Projeto

Este é o repositório para o projeto **Mandattum - Residência III**. 

## 🛠️ Tecnologias Utilizadas

A lista a seguir são as principais tecnologias e frameworks utilizados neste projeto:

* **Linguagem:** JavaScript
* **Framework:** React, Node.js, Express e Typescript 
* **Banco de Dados:** PostgreSQL
* **Outras Ferramentas:** GitHub Pages

## 🚀 Como Executar o Projeto

Siga os passos abaixo para ter uma cópia local do projeto em execução.

### Pré-requisitos

Certifique-se de que você tem instalado em sua máquina:

* Node.js e npm
* Express.JS

### Instalação

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/SidneyBarbosa/resid.git
    ```

2.  **Configuração de Variáveis de Ambiente:**
    Crie um arquivo `.env` na pasta "backend" e adicione as seguintes informações:
    ```.env
    # Configuração do Banco de Dados 
    DB_USER=postgres
    DB_HOST=localhost
    DB_DATABASE=postgres
    DB_PASSWORD=root
    DB_PORT=5432

    # Segredo da Aplicação
    JWT_SECRET=
    ```
    
3.  **Vá até o diretório:**
    * **Após abrir a pasta em uma IDE, abra um terminal powershell, para acessar as pastas Frontend e Backend, e rode os comandos (uma linha por vez):**
    * Abre a pasta principal:
    ```powershell
    cd vereador-lucio-gestao-politica 
    ```
    Abre a pasta beckend:
    ```powershell
    cd vereador-lucio-gestao-politica/beckend
    ```
    Em outro terminal, abra a pasta frontend:
    ```powershell
    cd vereador-lucio-gestao-politica/frontend
    ```
    
4.  **Instale as dependências e inicie o projeto:**
    * **No terminal na pasta Backend, execute os comandos:**
    ```powershell
    cd vereador-lucio-gestao-politica/beckend npm install
    ```
    ```powershell
    cd vereador-lucio-gestao-politica/beckend npm start
    ```
    Seu backend está pronto!

    **No terminal na pasta Frontend, execute os comandos:**
    ```powershell
    cd vereador-lucio-gestao-politica/frontend npm install
    ```
    ```powershell
    cd vereador-lucio-gestao-politica/frontend npm start
    ```
    Seu frontend está pronto! Ele deve abrir automaticamente no seu navegador (localhost).

5.  **Faça login:**
   * Email: admin@teste.com
   * Senha: Eduardo2025

## 📂 Estrutura do Repositório

O projeto segue a seguinte estrutura de diretórios:

* vereador-lucio-gestao-politica/
* ├── backend/
* │   ├── migrations/
* │   │   └── 20251106082004_create_initial_tables.js
* │   ├── node_modules/
* │   ├── src/
* │   │   ├── controllers/
* │   │   │   ├── acaoController.js
* │   │   │   ├── AuthController.js
* │   │   │   ├── chatbotController.js
* │   │   │   ├── contatoController.js
* │   │   │   ├── DashboardController.js
* │   │   │   ├── eleicoesController.js
* │   │   │   ├── financeiroController.js
* │   │   │   ├── municipioController.js
* │   │   │   ├── tarefaController.js
* │   │   │   └── userController.js
* │   │   ├── database/
* │   │   │   └── db.js
* │   │   ├── middlewares/
* │   │   │   └── authMiddleware.js
* │   │   ├── models/
* │   │   │   ├── acaoModel.js
* │   │   │   ├── contatoModel.js
* │   │   │   ├── dashboardModel.js
* │   │   │   ├── eleicaoModel.js
* │   │   │   ├── financeiroModel.js
* │   │   │   ├── tarefaModel.js
* │   │   │   └── userModel.js
* │   │   ├── routes/
* │   │   |    ├── api.js
* │   │   |    └── index.js
* │   │   ├── app.js
* │   │   └── test-bcrypt.js
* │   ├── .env
* │   ├── knexfile.js
* │   ├── package.json
* │   └── package-lock.js
* │
* ├── frontend/
* │   ├── node_modules/
* │   ├── public/
* │   │   └── index.html
* │   ├── src/
* │   │   ├── assets/
* │   │   │   ├── segipe.jpg
* │   │   │   └── sergipe-conexao123.jpg
* │   │   ├── components/
* │   │   │   ├── AcaoFormModal.js
* │   │   │   ├── Actions.js
* │   │   │   ├── AdminUsuarios.js
* │   │   │   ├── AlteracaoSenha.js
* │   │   │   ├── Cadastro.js
* │   │   │   ├── CadastroUsuario.js
* │   │   │   ├── ChatBot.js
* │   │   │   ├── Configuracoes.js
* │   │   │   ├── ConfirmModal.js
* │   │   │   ├── ContatoForm.js
* │   │   │   ├── Dashboard.js
* │   │   │   ├── DataMap.js
* │   │   │   ├── Eleicoes.js
* │   │   │   ├── Financeiro.js
* │   │   │   ├── Header.js
* │   │   │   ├── HeatmapLayer.js
* │   │   │   ├── Login.js
* │   │   │   ├── MapPage.js
* │   │   │   ├── MeusDados.js
* │   │   │   ├── NovoContatoForm.js
* │   │   │   ├── PrivateRoute.js
* │   │   │   ├── ProtectedRoute.js
* │   │   │   ├── ResultadosBairro.js
* │   │   │   ├── Sidebar.js
* │   │   │   ├── TaskForm.js
* │   │   │   └── TaskManagement.js
* │   │   ├── services/
* │   │   │   └── api.js
* │   │   ├── styles/
* │   │   │   ├── AcaoFormModal.css
* │   │   │   ├── Actions.css
* │   │   │   ├── App.css
* │   │   │   ├── Cadastro.css
* │   │   │   ├── Chatbot.css
* │   │   │   ├── Configuracoes.css
* │   │   │   ├── ConfirmModal.css
* │   │   │   ├── Dashboard.css
* │   │   │   ├── Eleicoes.css
* │   │   │   ├── Financeiro.css
* │   │   │   ├── Global.css
* │   │   │   ├── Header.css
* │   │   │   ├── Login.css
* │   │   │   ├── MapPage.css
* │   │   │   ├── NovoContatoForm.css
* │   │   │   ├── Sidebar.css
* │   │   │   ├── TaskForm.css
* │   │   │   └── TaskManagement.css
* │   │   ├── App.js
* │   │   └── index.js
* │   ├── package-lock.json
* │   └── package.json
* ├── .gitignore
* └── README.md
