# **Projeto para criar com o NodeJS uma API REST**

## Comandos para começar a criar a API:

`$ npm init -y`

 `$ npm install express body-parser sequelize mysql2`

`$ npm install config`

`$ node api/index.js`

`A API está funcionando!`

Para instalar tudo o que o projeto precisa basta digita no terminal o seguinte comando:

`npm i`

Para instalação do do nodemon, basta digitar o seguinte comando no terminal:

`$ npm insall --save-dev nodemon`

Depois de finalizada a instalação acesse o arquivo package.json e adicione ao módulo script a seguinte linha:

`"scripts": { "start": "nodemon api/index.js", "test": "echo \"Error: no test specified\" && exit 1" }` 

Para instalar a biblioteca para trabalhar com o XML no NodeJS, basta digitar o seguinte comando no terminal:

`$npm install jsontoxml`

Agora no terminal para executar o projeto basta digitar:

`npm start`



## Criando as tabelas do Banco de Dados.

Digite os seguintes comandos:

`$ node api/banco-de-dados/criarTabelas.js`

Saída da criação:

	Executing (default): CREATE TABLE IF NOT EXISTS `fornecedores` (`id` INTEGER NOT NULL auto_increment , `empresa` VARCHAR(255) NOT NULL, `email` VARCHAR(255) NOT NULL, `categoria` ENUM('ração', 'brinquedos') NOT NULL, `dataCriacao` DATETIME NOT NULL, `dataAtualizacao` DATETIME NOT NULL, `versao` INTEGER NOT NULL DEFAULT 0, PRIMARY KEY (`id`)) ENGINE=InnoDB;
	Executing (default): SHOW INDEX FROM `fornecedores`
	Tabela criada com sucesso




## Memorial descritivo do que foi realizado no Projeto.

- Criado a API em NodeJS;

- Gerenciado requisições e métodos da API;

- Trabalho com o formato de dados JSON em JavaScript;

- Gerenciamento de conexão com banco de dados;

- Representado tabelas do MySQL em código.

- Crie os métodos de requisição HTTP;

- Organizado a API em arquivos separados;

- Nomeado as rotas e caminhos da API;

- Criado validação de informações.

- Utilizado o método DELETE para remover dados;

- Nomeado uma URL para remover dados;

- Definido o Status de resposta para casos de sucesso diferentes;

- Definido o Status de resposta para casos de erro diferentes.

- Reconhecido erros comuns da API;

- Customizados as respostas de erros com JavaScript;

- Usado middlewares na API petshop com express;

- Tratado erros com JavaScript.

- Realizado trabalho com JSON e XML em NodeJS;

- Juntado listas em JavaScript;

- Implementado novos formatos no serializador.

- Aplicado Stores de uma API RESTful;

- Criado o Relacionamento de tabelas com Sequelize;

- Definido as rotas e hierarquia de dados em uma API RESTful;

- 

  
