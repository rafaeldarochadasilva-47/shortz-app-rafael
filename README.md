# Shortz-App 🔗

> Aplicação de encurtamento de URLs desenvolvida para a disciplina de Testes de Software

## 📋 Sobre o Projeto
Shortz-App é uma aplicação web que permite encurtar URLs longas, facilitando o compartilha

## 🎯 Objetivos de Aprendizagem

- Test-Driven Development (TDD)
- Testes unitários com Jest
- Testes de integração
- Integração Contínua com GitHub Actions
- Boas práticas de versionamento

## 🛠️ Tecnologias

- **Backend:** Node.js + Express
- **Banco de Dados:** PostgreSQL
- **Testes:** Jest + Supertest
- **CI/CD:** GitHub Actions

## 📁 Estrutura do Projeto

shortz-app/
├── bin/
│   └── www               (entry point da aplicação)   
├── config/
│   └── database.js       (configuração de acesso ao banco de dados via sequelize)
├── middlewares/          (vazia por enquanto)   
├── modules/              (vazia – virá nas próximas semanas)    
|── node_modules/         (pacotes do node, instalados via 'npm install ...')    
├── public/               (arquivos acessíveis diretamente via alguma url)    
│   ├── images/
│   ├── javascripts/
│   ├── stylesheets/
│   └── uploads/
│       ├── videos/  
│       └── covers/
├── routes/             (controladores de rotas para a aplicação)  
│   ├── index.js
│   └── users.js
├── views/              (parte visual - páginas - da aplicação)  
│   ├── layouts/
│   ├── partials/
│   ├── erros.ejs
│   └── index.ejs
├── .env                (chaves e senhas da aplicação - nunca publique este arquivo)  
├── .gitignore          (lista de arquivos que não devem ser publicados no GitHub)  
├── app.js              (setup básico da aplicação)  
└── package.json        (lista de dependências e scripts da aplicação)

## 🚀 Como Executar

### Pré-requisitos

- Node.js 18+ instalado
- MySQL instalado
- Git instalado

### Instalação

1. Clone o repositório:

  git clone https://github.com/seunome/shortz-app-seunome.git

2. Instale as dependências:

  npm install

3. Configure as variáveis de ambiente:
   
  .env.example .env
  # Edite .env com suas configurações

4. Execute o projeto:
   
  npm start

## ✅ Executando os Testes

# Todos os testes
npm test

# Testes com coverage
npm run test:coverage

# Modo watch (desenvolvimento)
npm run test:watch

## 📝 Progresso

- [x] Estrutura inicial
- [ ] Configuração do banco de dados
- [ ] Implementação da API
- [ ] Testes unitários
- [ ] Testes de integração
- [ ] CI/CD

## 👨🏻‍💻 Autor

Rafael da Rocha da Silva
Estudante de Engenharia de Software  
Turma 2026

## 📄 Licença

Este projeto foi desenvolvido para fins educacionais.

### Salvar e commitar:

git add README.md
git commit -m "Atualiza documentação do README"
git push
