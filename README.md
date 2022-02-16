# Base de conhecimento <sub><sup>- Vue fundamentals</sup></sub>
<sub>Readme available in English.</sub>

Projeto realizado na finalização do curso, que visa criar experiência com o desenvolvimento de soluções Front-end usando VueJS e APIs usando Node.JS.</br>
<sub>Project made in the end of the course, aiming to make the student experience what it's like to develop solutions using Front-end VueJS and Back-end Node.JS APIs.</sub> 


# Como rodar as aplicações? <sub><sup>- How to run the applications?</sup></sub>

## Clone este repositório <sub><sup>- Clone this repository</sup></sub>
```
git clone https://github.com/ChrystianFerreira/cod3r_knowledge_vuejs
```

Baixe o MongoDB acessando o seguinte link: https://www.mongodb.com/try/download/community;</br>
Acesse o diretório de instalação do MongoDB (C:\...\MongoDB\Server\5.0\bin) e rode o arquivo mongod.exe!

Versão usada: 5.0

<sub>Download MongoDB from the link above, access the installation directory and run the mongod.exe file! </br>Version used: 5.0</sub>

## Entre no repositório <sub><sup>- Enter repository</sup></sub>
```
cd cod3r_knowledge_vuejs
```

## Selecione o diretório do aplicação desejada <sub><sup>- Enter directory of desired application</sup></sub>

```
cd versao-inicial
```

e então escolha entre: <span>```cd backend``` ou ```cd frontend```</span></br> <sub> Choose between these options </sub>

### Instale as dependências <sub><sup>- Install dependencies</sup></sub>

```
npm ci
```

### Rode o front-end <sub><sup>- Run front-end</sup></sub>
```
npm run serve
```

### Rode o back-end <sub><sup>- Run back-end</sup></sub>
```
npm run start
```

## Tecnologias usadas <sub><sup>- Technology used</sup></sub>

### Back-end
<strong>Node.JS</strong> com <strong>Express</strong>;</br>
<strong>Banco de dados PostgreSQL/MongoDB</strong>;</br>
Middlewares e principais dependências:
  <li><strong>Knex</strong>, ajudando na construção de queries SQL; <sub>- SQL Query Builder</sub> </li>
  <li><strong>Passport</strong> para <strong>autenticação</strong>; <sub>- Used for authentication</sub></li>
  <li><strong>Mongoose</strong>;</li>
  <li>Body parser, interpretador de body de requisições;</li>
  <li>CORS;</li>
  <li>Consign, ajudando a evitar múltiplos 'require' em toda aplicação, injetando todos nossos middlewares na aplicação de maneira prática.</li>
  <sub>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- Consign helps with avoiding using 'require' multiple
  times all over the app by injecting our middlewares in an easy way.</sub>
  
  ### Front-end
  <li><strong>Vue</strong></li>
  <li><strong>VueX</strong></li>
  <li><strong>Bootstrap-vue</strong></li>
  <li><strong>Vue toasted</strong></li>
  
  # Curso na Udemy<sub><sup> - Course on Udemy</sup></sub>
  ## https://www.udemy.com/course/vue-js-completo/
