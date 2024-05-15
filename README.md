# apiflutter

Este aplicativo é uma api que administra uma lista de usuários, com base de dados importado da url ’https://dummyapi.io/data/v1/, e desenvolvida em Flutter no Visual Studio Code’. Sua tela principal exibe a lista de usuários e as opções de edição e exclusão por usuário, e um botão flutuante para adicionar um novo usuário.

## Arquivos de código-fonte

A pasta /lib possui três arquivos de código, main.dart, user.dart e user_service.dart.

### user.dart

Compõe a classe base ("User") para a api, possuindo os campos (em português): id; título; nome; sobrenome; email; foto. E os métodos para converter em Json e de Json.

### user_service.dart

Arquivo Service (Controlador) da api, fazendo a conexão com a base de dados remota e criando os métodos base para uma api, tais como criar, atualizar, excluir e evidenciar um User ou exibir todos os Users.

### main.dart

Arquivo de código que roda o programa, cria as exibições (telas) e interações (ações).

#### Explicação do código

O Scaffold da tela principal tem como body o Widget '_buildUserList()' e o floatingActionButton o Widget '_addUserButton()',
