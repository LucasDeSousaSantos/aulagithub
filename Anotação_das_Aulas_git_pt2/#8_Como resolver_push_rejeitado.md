# Como resolver push rejeitado (git pull)

Para realizar um `push` no seu projeto, o seu repositorio local deve estar sincronizado com o repositorio remoto. Ou seja, se o seu repositorio local estiver atrasado em relação ao repositorio remoto, não será permitido fazer o `push`.

Para resolver este problema, precisamos usar o comando `git pull <nome do remote> <nome do branch>`, que trará os arquivos que estão no repositorio remoto para o seu repositorio local, dessa forma, organizando todos os commits de forma cronologica.

Ao utilizar o comando, um editor de texto será aberto pelo terminal com a mensagem de um commit adicional que é necessario para realizar a operação. Após isso, os repositorio estarão sincronizados no mesmo ponto e você poderá realizar novos `git push` normalmente.