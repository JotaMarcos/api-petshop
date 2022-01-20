# **Projeto para criar com o NodeJS uma API REST**

Comandos para começar a criar a API:

`$ npm init -y`

 `$ npm install express body-parser sequelize mysql2`

`$ npm install config`

`$ node api/index.js`

`A API está funcionando!`

Criando as tabelas do Banco de Dados.

Digite os seguintes comandos:

`$ node api/banco-de-dados/criarTabelas.js`

Saída da criação:

	Executing (default): CREATE TABLE IF NOT EXISTS `fornecedores` (`id` INTEGER NOT NULL auto_increment , `empresa` VARCHAR(255) NOT NULL, `email` VARCHAR(255) NOT NULL, `categoria` ENUM('ração', 'brinquedos') NOT NULL, `dataCriacao` DATETIME NOT NULL, `dataAtualizacao` DATETIME NOT NULL, `versao` INTEGER NOT NULL DEFAULT 0, PRIMARY KEY (`id`)) ENGINE=InnoDB;
	Executing (default): SHOW INDEX FROM `fornecedores`
	Tabela criada com sucesso
- Criamos uma API em NodeJS;
- Gerenciamos requisições e métodos em uma API;
- Trabalhamos com o formato de dados JSON em JavaScript;
- Gerenciamento de conexão com banco de dados;
- Representar tabelas do MySQL em código.
- Criei os métodos de requisição HTTP;
- Organizei a API em arquivos separados;
- Nomeie rotas e caminhos da API;
- Criei validação de informações.
- Utilizado o método DELETE para remover dados;
- Nomeado uma URL para remover dados;
- Definido o Status de resposta para casos de sucesso diferentes;
- Definido o Status de resposta para casos de erro diferentes.

