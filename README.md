README da Aplicação Pizzaria
Projeto A3
Visão Geral
Nosso projeto semestral, é sobre um sistema de gerenciamento para cadastro e consulta de produtos, como de pizzas e bebidas, para a rede Pizza Hut, também conta com uma tela de login para limitação de uso aos funcionários da pizzaria. Desenvolvida em Java Swing, a aplicação oferece funcionalidades para adicionar, remover, buscar e editar pizzas, bebidas e usuários.

Conteúdo do Projeto

Pizzas.java
•	Descrição: O frame principal para o gerenciamento de pizzas.
•	Funcionalidades:
•	Exibição de uma tabela com informações detalhadas sobre pizzas.
•	Adição de novas pizzas.
•	Remoção de pizzas existentes.
•	Busca de pizzas por nome.
•	Edição de detalhes de pizzas.
•	Dependências:
•	DB.java: Manipula operações de banco de dados.
•	TableRender.java: Renderiza dados no componente JTable.

Bebidas.java
•	Descrição: O frame principal para o gerenciamento de bebidas.
•	Funcionalidades:
•	Exibição de uma tabela com informações detalhadas sobre bebidas.
•	Adição de novas bebidas.
•	Remoção de bebidas existentes.
•	Busca de bebidas por nome.
•	Edição de detalhes de bebidas.
•	Dependências:
•	DB.java: Manipula operações de banco de dados.
•	TableRender.java: Renderiza dados no componente JTable.
LoginUsuario.java
•	Descrição: Lida com o processo de login do usuário.
•	Funcionalidades:
•	Autenticação do usuário.
•	Controle de acesso a outras partes da aplicação.
DB.java
•	Descrição: Manipula operações de banco de dados SQLite.
•	Funcionalidades:
•	Conexão ao banco de dados (bancodados.db).
•	Execução de consultas e instruções SQL.

TableRender.java
•	Descrição: Classe para renderizar dados no componente JTable.
•	Funcionalidades:
•	Renderização de colunas e campos da tabela.

Banco de Dados
•	Nome do Banco de Dados: bancodados.db
•	Tabelas:
•	pizzas: Colunas - "codigo," "nome," "ingredientes," "preço."
•	bebidas: Colunas - "codigo," "fornecedor," "produto," "alcoolico," "tamanho."
• usuários: Colunas - "id," "usuario," "senha"

Uso
Pizzas.java
•	Nova Pizza: Clique em "NOVA PIZZA" para adicionar uma nova pizza.
•	Remover Pizza: Selecione uma pizza e clique em "REMOVER" para excluí-la.
•	Procurar Pizza: Digite o nome de uma pizza e clique em "BUSCAR" para pesquisar.
•	Editar Pizza: Selecione uma pizza e clique em "ALTERAR" para editar detalhes.

Bebidas.java
•	Nova Bebida: Clique em "NOVA BEBIDA" para adicionar uma nova bebida.
•	Remover Bebida: Selecione uma bebida e clique em "REMOVER" para excluí-la.
•	Procurar Bebida: Digite o nome de uma bebida e clique em "BUSCAR" para pesquisar.
•	Editar Bebida: Selecione uma bebida e clique em "ALTERAR" para editar detalhes.

LoginUsuario.java
•	Insira o nome de usuário e senha para fazer login.
Configuração e Execução
1.	Abra o projeto em um IDE Java, como NetBeans.
2.	Execute o arquivo LoginUsuario.java.

Integrantes
•	Kessia de Fatima Araujo Brito / R.A. – 823.119.109
•	Lucas Eduardo Barreto de Oliveira / R.A. – 823.122.774
•	Grazielli Soares Pereira / R.A - 82320977

