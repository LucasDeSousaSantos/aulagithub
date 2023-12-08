# Como apontar o projeto para outro repositorio remoto

Você pode apontar as atualizações do seu projeto para outro repositorio caso seja necessario: 

Para fazer isso, utilizamos o comando: `git remote set-url origin git@github.com:LucasDeSousaSantos/aulateste.git`

o "set-url" é o comando que indica para onde o repositorio local deve apontar. Em seguida, insira o apelido do repositorio (origin) e a chave SSH dele

Em seguida, utilize o comando `git push -u origin main` como primeiro push

Dica: Utilize o comando `git remote -v` para saber para onde o repositorio local esta apontando.