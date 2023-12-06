# Git Status, git add e Git stage

### git status

ao utilizar o comando `git status` podem ocorrer três situações:

- modified: Alguma modificação em um arquivo

- untracked: Arquivos novos que ainda não estão salvos

- deleted: Arquivos deletados

### Stage

Utilizando o comado `git add .` adicionamos todas as modificações a área de stage, isso significa que preparamos os arquivos modificados para serem "commitados"

A área de stage permite que você selecione quais arquivos serão salvos no novo commit.
Por exemplo, se você tem 5 arquivos novos e 5 arquivos modificados, é possivel addicionar 5 desses arquivos separadamente com uma mensagem "modificado", ou "novo arquivo criado", sem precisar commitar tudo de uma vez. A área de stage permite um maior controle de versionamento para o programador.

Em outras palavras, podem escolher o que será salvo em nosso repositorio remoto (git hub)

### Git reset

Utilizando o comando `git reset` retiramos os arquivos da área de stage

### Git add .

Utilizando o comando `git add .`, adicionamos todas as alterações ao stage. Para selecionar o que queremos por na área de stage, utilizamos o comando `git add <nome do arquivo modificado>`