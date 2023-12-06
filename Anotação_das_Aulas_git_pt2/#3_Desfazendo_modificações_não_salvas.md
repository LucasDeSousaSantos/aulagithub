# Como desfazer modificações não salvas

Caso você mude algo e se perca, é possivel apagar as modificações desde do ultimo commit realizado. Em outras palavras, é possivel voltar o projeto no estado em que estava no ultimo commit.

Para fazer isso, utilize os seguintes comandos:

- `git reset`: para retirar os arquivos da area de Stage
- `git clean -df`
- `git checkout -- .`: Limpa todas as modificações