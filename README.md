# Viagens

## ✨ Sobre o projeto

O Projeto **Viagens** foi criado para consolidar/praticar os conhecinentos de **Frontend**, **Context API** e **Backend**.

## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [React](https://reactjs.org/)
- [Context API](https://reactjs.org/docs/context.html)
- [TypeScript](https://www.typescriptlang.org/)
- [Node.js](https://nodejs.org/en/)

## 💻 Como executar

- Clone o repositório `git clone https://github.com/SouzaVitoria/Viagens`
- Entre nas pastas (front-end / back-end ) e instale as dependências utilizando `npm install`
  > Não se esqueça de que para o frontend funcionar e enviar corretamente o feedback, o backend precisa estar rodando.

### 🖥 Frontend

- Entre na pasta front-end e rode o comando `npm start`.
  > No terminal irá mostrar em qual endereço que o projeto estará rodando, e automaticamente abrirá no seu navegador.

### ⚙ Backend

- Entre na pasta back-end e rode o comando `npm start`.


## 📚 Ferramentas, Bibliotecas e Pacotes

### 🖥 Frontend

- **Vite:** é uma ferramenta que converte o código para um formato que todos os browsers entendam, ou seja, permite que o navegador entenda o JS mais moderno.


⚙ Backend
ts-node-dev: pacote integrado com TS, quando houver qualquer alteração em algum arquivo, reinicia o servidor automaticamente (faz o mesmo que o Nodemon)

Express: "mini-framework/biblioteca", para trabalhar com a parte http do backend, lidar com rotas.

Banco de Dados:

Utilização do SQLite em desenvolvimento e o Postgresql em produção

SQLite não precisa instalar nada na máquina, ele salva o BD como um arquivo fixo.

Prisma: Prisma é um ORM, ou seja, é uma ferramenta que facilita para trabalhar com operações com banco de dados. É uma forma e abstrar como nos comunicamos com o BD, ou seja, em vez de escrevermos querys SQLs tradicionais, vamos escrever códigos JS e ele irá converter no SQL tradicional.

O Prisma suporta múltiplos BD, então se fizer a transição entre esses BD, não precisamos alterar o código

Enviar e-mail:

nodemailer
Mailtrap: serviço para envios de e-mails

CORS: biblioteca que basicamente é uma forma de fazer controles de segurança no backend para que não permita que frontends inadequados acessem as informações do backend. Conseguimos colocar exatamente quais endereços de frontend que podem consumir/acessar o backend

Testes unitários (Jest): é um framework de testes

Para ter arquivos de configuração do Jest que seja TS, precisa instalar ts-node > SWC: O Jest por padrão, só entende arquivos JS, então precisamos permitir que o Jest entenda arquivos TS, utilizando o @swc/jest (ts-jest e babel também são compiladores JS, mas são bem lentos em comparação ao swc)


## 👨🏻‍💻 Contribuição

Quer contribuir com este projeto? Então siga os passos abaixo:

1. Realize o fork do projeto
2. Crie sua branch (git checkout -b feature/AmazingFeature)
3. Faça o commit das suas modificações/criações (`git commit -m 'Add some AmazingFeature'`)
4. Publique a branch (git push origin feature/AmazingFeature)
5. Abra uma Pull Request

## 📄 Licença

Este projeto não utiliza nenhum tipo de licença.
