<h2 align="center">  
Projeto Final de Backend - Labenu Music Awards🎸
</h2>

<h4 align="center">  
Este projeto tem como objetivo criar uma API para o gerenciamento de um festival de música. Onde podemos cadastrar um usuário, cadastrar atrações musicais e efetuar reservas de ingressos. A API foi desenvolvida utilizando as tecnologias Node.JS, Typescript, Express.JS, MySQL, Jest para testes unitários e foi estruturado com Programação Orientada a Objetos(POO).
</h4>

### Endpoints:
- Signup
- Login
- Create Show
- Get Shows
- Book a Ticket
- Delete Ticket 

## ✔️ Funcionalidades:
- Cadastro: Onde é permitido o registro de um usuário. Para isso é necessário informar nome, email e senha validos
- Login: Para realizar o login, basta informar seu e-mail e senha. O retorno deve conter o token de autenticação do usuário
- Cadastrar Show: Onde é permitido o registro de um show. Para isso é necessário informar nome e data da apresentação. Duas atrações não podem tocar em um mesmo dia e somente administradores podem fazer o registro
- Detalhes do Show:  Após o registro cada atração recebe um ID, a partir dele é possivel visualizar também o nome, data e quantidade de ingressos disponíveis
- Reserva de ingressos: O sistema deve permitir a reserva de ingressos. Cada usuário pode reservar apenas 1 ingresso por show
- Cancelamento da Reserva: O sistema deve permitir o cancelamento da reserva. Onde cada pessoa só pode deletar suas próprias reservas
- Todos os endpoints foram testados e aprovados
- Todos os erros foram testados e aprovados

## 📄Documentação

- [LINK POSTMAN](https://documenter.getpostman.com/view/21551971/2s83tDoY1D)

Os endpoints também podem ser testados diretamente no arquivo ``requests.rest``

## 💻Como Rodar o Projeto Localmente

- Para rodar o projeto é necessário a instalação prévia do [Node.JS](https://nodejs.org/en/download/)
- Um editor para trabalhar com o código como: [VSCode](https://code.visualstudio.com/)
- Uma instancia de banco de dados MySQL

Siga o passo-a-passo abaixo:

| Passo                     | Comando            |
| ------------------------- | ------------------ |
| Faça o Clone              | `git clone`  deste repositório |
| Instale as Dependências   | `npm install`  ou  ` yarn install` |
| Utilize o Script NPM  | `npm run start`  ou  `npm run dev` |
|Para rodar os testes   | `npm run test`  ou  `npm test` |

Para aplicação funcionar corretamente é necessário criar um arquivo ```.env``` na raiz do projeto e preencher as variáveis com seus dados do banco de dados MySQL.

## 🛠 Tecnologias utilizadas

- Typescript;
- Express;
- Cors;
- Knex; 
- SQL
- Jest

## 📚 Aplicações utilizadas

- VSCode
- Workbench MySQL
- Heroku
- Postman

<h2 align="center"> 
 👩🏻‍💻Desenvolvedora 
</h2>

<table align="center">
  <tr>
    </td> <td align="center"><a href="https://github.com/Mariandr4de"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/104591781?v=4" width="100px;" alt=""/><br /><sub><b>Mariana Andrade</b></sub></a> 
  </tr>
</table>

