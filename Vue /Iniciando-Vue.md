# Iniciando com Vue

## Uma pequena conversa

Atualmente é um dos frameworks mais usados pela comunidade. O Vue-JS tem como foco principal  a construção de componentes e SPA (Single Page Aplication). Você pode trabalhar com este framework de duas maneiras pelo método tradicional usando a tag script e pelo CLI (Command Line Interface), veja abaixo as duas formas (Obs: no caso do uso de CLI é obrigatório que você tenha em sua máquina npm e NodeJS instalados)

Método por tag:  <script src ="https://cdn.jsdelivr.net/npm/vue"></ script>

Método por CLI: npm install vue-cli -g (Detalhe importante: -g é uma instalação goblal! Então é necessário que você esteja em super usuário para está opção.)

## Iniciando nossa aplicação “Hello World”

 Para iniciar uma aplicação, crie uma pasta na Área de trabalho chamada de Projeto_Vue. Logo após   criada a pasta abra a mesma no terminal pelo comando CD + caminho diretório. Feito essas etapas então digite os seguintes comandos no terminal ou CMD:

Vue init webpack-simple  Hello-World

### Entendendo em partes o que aconteceu no terminal<br>

O comando que digitamos acima é para criarmos uma aplicação usando o template (webpack-simple), que no nosso caso seria uma aplicação básica. Após digitarmos o comando e mandarmos um enter, irá aparecer algumas perguntinhas básicas para você colocar o nome do projeto, autor e descrição. Mesmo feito essas partes ainda precisamos digitar mais alguns comando em nosso terminal para que possa em fim rodarmos nossa aplicação com Vue, são eles:

cd Hello-World //Para abrir a pasta da aplicação
npm install //Baixar os pacotes
npm run dev //Executa o projeto no navegador

 Por fim então temos executando em nosso navegador um index de apresentação do Vue.