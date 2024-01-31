```javascript
DESAFIO:
História do Usuário: APP de Tarefas
Como um usuário,
eu quero ser capaz de gerenciar minha lista de tarefas de forma eficiente,
para que eu possa acompanhar e concluir minhas atividades diárias.
 1.  Escreva cenários BDD para a história do usuário. Utilize o formato "Dado, Quando, Então" para descrever o 	comportamento esperado da aplicação.
 2.  Escreva casos de teste para cobrir diferentes aspectos da aplicação, incluindo casos positivos e negativos.
 3.  Coloque o seu BDD e Casos de teste no github

 ______________________________________________________________________________________________________________________

Funcionalidade: gerenciar lista de tarefas
-Como um usuário
-Eu quero ser capaz de gerenciar minha lista de tarefas de forma eficiente
-Para que eu possa acompanhar e concluir minhas atividades diárias.
    
    
Cenário: CRIAR TAREFA
 Dado que o usuário abra o app
 Quando ele selecionar o botão criar lista de tarefas
 Então poderá criar uma nova lista de tarefas

Cenário: EDITAR TAREFA
 Dado que o usuário tenha uma lista de tarefas
 Quando ele clicar duas vezes em uma das tarefas
 Então poderá editar a tarefa selecionada

Cenário: EXCLUIR TAREFA
 Dado que o usuário tenha uma lista de tarefas
 Quando ele clicar em uma das tarefas
 E selecionar o botão excluir
 Então a tarefa deve ser apagada

Cenário: ALTERAR O STATUS DE UMA TAREFA  PARA “CONCLUÍDA”
 Dado que o usuário tenha uma lista de tarefas
 Quando ele clicar em uma das tarefas
 E selecionar o botão concluir
 Então a tarefa deve ser marcada como concluída
 E a mesma deve ir para o final da lista com a cor verde

Cenário: ALTERAR O STATUS DE UMA TAREFA  PARA “ADIADA”
 Dado que o usuário tenha uma lista de tarefas
 Quando ele clicar em uma das tarefas
 E selecionar o botão adiar
 Então a tarefa deve ser marcada como adiada
 E a mesma deve ir para o início da lista com a cor vermelha

Cenário: ALTERAR O STATUS DE UMA TAREFA  PARA “EM ANDAMENTO”
 Dado que o usuário tenha uma lista de tarefas
 Quando ele clicar em uma das tarefas
 E selecionar o botão em andamento
 Então a tarefa deve ser marcada como em andamento
 E a mesma deve ir para o início da lista com a cor azul

```

Print "Cenários de Teste"

![Captura de tela 2024-01-31 193803](https://github.com/karlamoraess/cenarios-de-teste/assets/147740711/78dab86f-8c7b-4585-a092-a905506e338d)
