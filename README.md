# 🏢 LocService - Marketplace de Serviços para Condomínios

Sistema web completo para conectar prestadores de serviços locais a moradores de condomínios. Permite cadastro de empresas, autenticação segura e busca por categoria de serviços.


## 📖 Sobre o Projeto

O **LocService** é uma plataforma web desenvolvida para facilitar a conexão entre prestadores de serviços e moradores de condomínios. O sistema permite que empresas cadastrem seus serviços e clientes possam encontrar prestadores confiáveis de forma prática e segura.

### Problema Resolvido

Moradores de condomínios enfrentam diversos desafios ao buscar prestadores de serviços confiáveis:

#### 🔍 **Dificuldade de Encontrar Prestadores**
A busca por serviços essenciais como jardinagem, limpeza, manutenção e pet care geralmente acontece de forma desorganizada, através de indicações boca a boca, grupos de WhatsApp ou pesquisas aleatórias na internet, consumindo tempo e gerando frustração.

#### ⚠️ **Falta de Confiança e Segurança**
Contratar serviços de terceiros sem referências concretas gera insegurança. Moradores ficam receosos quanto à qualidade do trabalho, idoneidade do prestador e segurança ao permitir acesso ao condomínio e suas residências.

#### 📱 **Ausência de Centralização**
Não existe uma plataforma única que concentre informações sobre prestadores de serviços locais. As informações ficam dispersas em murais físicos, grupos de mensagens e páginas de redes sociais, dificultando o acesso e comparação.

#### 🤝 **Falta de Avaliação e Histórico**
Sem um sistema de reputação, é difícil saber se o prestador é recomendado por outros moradores, quantos serviços já realizou no condomínio ou qual seu nível de satisfação entre os clientes.

#### 💰 **Dificuldade de Comparação**
Moradores não conseguem comparar facilmente diferentes prestadores da mesma categoria, seus diferenciais, especialidades e formas de contato, levando a escolhas menos informadas.

#### 🏢 **Desafio para Prestadores Locais**
Do outro lado, pequenas empresas e autônomos de qualidade têm dificuldade em se divulgar dentro dos condomínios, perdendo oportunidades de negócio mesmo estando próximos geograficamente.

#### ✅ **Solução: LocService**
O LocService resolve esses problemas ao oferecer:
- **Centralização:** Todas as informações em um único lugar acessível 24/7
- **Confiança:** Empresas cadastradas com informações verificáveis (categoria, descrição, contato)
- **Praticidade:** Busca rápida por categoria e nome, com acesso direto ao WhatsApp
- **Transparência:** Perfis completos com descrição dos serviços oferecidos
- **Acessibilidade:** Plataforma web responsiva, sem necessidade de downloads
- **Oportunidade:** Visibilidade para pequenas empresas locais alcançarem novos clientes

O sistema transforma o processo caótico de busca por serviços em uma experiência organizada, segura e eficiente, beneficiando tanto moradores quanto prestadores de serviços.

---

## ⚙️ Funcionalidades

### Para Visitantes (Sem Login)
- ✅ Visualizar lista de empresas cadastradas
- ✅ Filtrar empresas por categoria
- ✅ Buscar empresas por nome
- ✅ Acessar informações de contato (WhatsApp)

### Para Empresas (Com Login)
- ✅ Cadastrar-se na plataforma
- ✅ Fazer login seguro com autenticação JWT
- ✅ Editar informações do perfil (nome, categoria, descrição, WhatsApp) (em desenvolvimento)
- ✅ Visualizar dashboard personalizado (em desenvolvimento)

### Para Administradores
- ✅ Acesso completo ao sistema
- ✅ Gerenciar empresas cadastradas (em desenvolvimento)
- ✅ Visualizar estatísticas (em desenvolvimento)

---

## 🛠️ Tecnologias Utilizadas

### Backend
- **Node.js** v18.x - Ambiente de execução JavaScript
- **Express.js** v4.18.2 - Framework web para criação de APIs REST
- **MySQL** v8.0 - Sistema de gerenciamento de banco de dados relacional
- **bcryptjs** v2.4.3 - Biblioteca para criptografia de senhas
- **jsonwebtoken** v9.0.2 - Implementação de autenticação JWT (JSON Web Token)
- **dotenv** v16.3.1 - Gerenciamento de variáveis de ambiente
- **CORS** v2.8.5 - Middleware para controle de acesso entre origens
- **mysql2** v3.6.5 - Driver MySQL com suporte a Promises

### Frontend
- **HTML5** - Estrutura semântica das páginas
- **CSS3** - Estilização responsiva e moderna
- **JavaScript (ES6+)** - Lógica do cliente e comunicação com API
- **Fetch API** - Requisições HTTP assíncronas

### Ferramentas de Desenvolvimento
- **Visual Studio Code** - Editor de código
- **Live Server** - Servidor local para desenvolvimento frontend
- **Thunder Client** - Testes de API
- **Git** - Controle de versão
- **GitHub** - Repositório remoto

---

## 🏗️ Arquitetura do Sistema

O projeto segue o padrão **MVC (Model-View-Controller)** e arquitetura **cliente-servidor**.

---

## 📦 Pré-requisitos

Antes de executar o projeto, certifique-se de ter instalado:

### 1. Node.js
- **Versão:** 18.x ou superior
- **Download:** https://nodejs.org

### 2. MySQL
- **Versão:** 8.0 ou superior
- **Opções de instalação:**
  - MySQL Community Server: https://dev.mysql.com/downloads/mysql

### 3. Git
- **Download:** https://git-scm.com

### 4. Editor de Código (Opcional)
- **Visual Studio Code:** https://code.visualstudio.com
- **Extensões recomendadas:**
  - Live Server (para frontend)
  - Thunder Client (para testes de API)

---

## 🚀 Instalação e Configuração

**SEM TER O PROJETO BAIXADO:**
### Passo 1: Clonar o Repositório digitando no terminal do VSCode "git clone https://github.com/A3-Erivelton/LocService-A3.git". Em seguida, se direcione para a pasta LocService-A3 digitando "cd LocService-A3".
### Passo 2: Conferir se todos os arquivos foram clonados na máquina local, caso contrário ir para passo 2.1.
  ### Passo 2.1: Conferir a branch digitando "git branch". Se estiver na main, muda para a master digitando "git checkout master".
      obs: o projeto foi feito sem querer na branch master em vez da main.
  ### Passo 2.2: Fazer o download dos arquivos digitando "git pull origin master". Se der o erro "fatal: refusing to merge unrelated histories", ir para o passo 2.3.
  ### Passo 2.3: Faça o git pull digitando "git pull origin master --allow-unrelated-histories". Em seguida, digite ":wq" e dê Enter. Os arquivos serão baixados na máquina local.

**JÁ COM O PROJETO BAIXADO:**
### Passo 1: Estando, no terminal, na pasta "LocService-A3", entrar na pasta "backend" digitando "cd backend".
### Passo 2: Instalar os pacotes do node digitando "npm install".
### Passo 3: Abrir arquivo ".env.example" na pasta "backend". Copiar o conteúdo inteiro e criar um arquivo chamado ".env" na mesma pasta, no qual irá colar o conteúdo e alterar a senha do banco de dados na linha 9 em "DB_PASSWORD" para a senha do seu banco de dados.
### Passo 4: Executar no terminal script que cria o banco de dados digitando "npm run setup". 
  **Saída esperada:**
  📡 Conectando ao MySQL...
  ✅ Conectado ao MySQL!
  
  📖 Lendo arquivo database.sql...
  ⚙️ Executando script SQL...
  ✅ Script SQL executado com sucesso!
  
  ✅ Banco de dados 'locservice_db' criado/verificado!
  
  📊 Tabelas criadas:
  
      usuarios
  
  ✅ Setup concluído com sucesso!
  
### Passo 5: Executar no terminal script que popula o banco de dados com dados fictícios digitando "npm run seed".
  **Saída esperada:** (reduzimos aqui o texto esperado para economizar linhas)
  📡 Conectando ao MySQL...
  ✅ Conectado ao MySQL!
  
  🗑️ Limpando tabela usuarios...
  ✅ Tabela limpa!
  
  📝 Inserindo usuários...
  
  ✅ Administrador (admin@locservice.com)
  ✅ Jardins & Cia (jardins@locservice.com)
  ✅ Limpa Tudo (limpatudo@locservice.com)
  ✅ Repara Bem (reparabem@locservice.com)
  ✅ PetCare (petcare@locservice.com)
  ✅ Fitness Point (fitness@locservice.com)
  ✅ TechCondo (techcondo@locservice.com)
  ✅ Pão da Vila (paodavila@locservice.com)
  ✅ Conserta+ (consertamais@locservice.com)
  ====================================
  ✅ 9 usuários inseridos com sucesso!
  [...]
  💡 Dados de Login:
  Admin: admin@locservice.com / admin123
  Empresa: jardins@locservice.com / jardim123
  
  ✅ Seed concluído com sucesso!

### Passo 6: Executar o servidor backend digitando "npm run dev". O backend estará rodando. Mantenha o terminal aberto!!!!
  **Saída esperada:**
  ✅ Conectado ao MySQL!
  
  🚀 Servidor rodando na porta 3000
  📍 http://localhost:3000/api/health
  
  💡 Rotas disponíveis:
  POST /api/auth/register
  POST /api/auth/login
  GET /api/auth/me (protegida)
  PUT /api/auth/me (protegida)
  GET /api/empresas
  GET /api/empresas/:id
  GET /api/empresas/search?q=termo
  GET /api/empresas/stats
  
  ✅ Backend pronto para uso!

---

### Iniciar o Frontend

**Com Live Server (VSCode)**

1. Talvez, após o "git pull" o projeto estará dentro de uma pasta selecionada previamente com "Open Folder", o que acarretará desconfiguração do CSS no front. Se for o caso, clique em "Open Folder" e selecione a pasta "LocService-A3". Em seguida vá para 1.1.
   1.1 O backend irá se fechar, portanto entre na sua pasta pasta digitando "cd backend" e em seguida digite "npm run dev" novamente para subir o servidor backend.
2. Abra a pasta `frontend/` no VSCode
3. Clique com botão direito em `index.html`
4. Selecione **"Open with Live Server"**
5. Navegador abrirá automaticamente em `http://localhost:5500` ou `http://127.0.0.1:5501`.

---

## 🔌 Endpoints da API


### Autenticação

#### **POST /api/auth/register**
Cadastra nova empresa no sistema.

#### **GET /api/auth/me** 🔒
Retorna dados do usuário autenticado.

#### **PUT /api/auth/me** 🔒
Atualiza dados do usuário autenticado.


### Empresas (Rotas Públicas)

#### **GET /api/empresas**
Lista todas as empresas cadastradas.

#### **GET /api/empresas/:id**
Busca empresa por ID.

#### **GET /api/empresas/search**
Busca empresas por nome.

#### **GET /api/empresas/stats**
Retorna estatísticas de categorias.

---

## 👨‍💻 Autores

**Matheus Cavalcante Monteiro** - **RA** 1282421475
**Francisco Edglê Silverio de Oiveira** - **RA** 12824213212
**Alison Guilherme Graciano Ramalho** - **RA** 1282421073
**Jéssica Priscila Silva Da Rocha** - **RA** 1282421957

## 🙏 Agradecimentos

- Universidade Potiguar (UNP) pela infraestrutura
- Professores da disciplina pelo suporte
- Colegas de turma pela colaboração
- Comunidade open-source pelas bibliotecas utilizadas
