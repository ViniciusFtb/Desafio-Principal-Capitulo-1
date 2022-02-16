# Ignite - Trilha React: Desafio principal capítulo 1
Terminado o primeiro capítulo da trilha React do Ignite, estava ansioso para colocar em prática o que aprendi. Componentes, estado e imutabilidade são conceitos que eu sabia que devia dar bastante atenção.

Foi muito interessante entender a estrutura já pronta do projeto para que eu pudesse criar as funcionalidades propostas no desafio:
- handleCreateNewTask: 
  Criei um objeto e coloquei os dados necessários para formar a task. A dificuldade começou ao manipular o estado e perder a task criada sempre que se criasse uma nova.
  Pesquisando sobre useState, obtive a solução utilizando callbacks: o estado antigo é copiado e adicionado ao novo.
- handleToggleTaskCompletion: 
  Utilizei um map e uma estrutura if else bem simples, onde mais tive dificuldades foi na manipulação do estado ao atualizar as tasks. Durante a aula, o estado foi manipulado ao consumir uma api, dessa vez tive que manipulá-lo pensando no retorno gerado e nas alterações feitas.
  Com algumas pesquisas, cheguei à conclusão e, após manipular os dados da task, utilizei spread operator.
- handleRemoveTask: 
  Pesquisando sobre filter, cheguei à estrutura presente no código, onde se verifica o id de cada task e remove as tasks com o id desejado.
  
Durante as aulas tudo ficou muito claro, porém o desafio mostrou seu valor e deixou bem claro minhas dificuldades ao resolver cada tarefa. 
