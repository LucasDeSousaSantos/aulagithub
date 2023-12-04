# Git checkout

- Codigo do commit: Todo commit tem um codigo "identificador"
- Head: O "head" é o ultimo commit salvo

O comando `git checkout <codigo do commit>` altera temporariamente os dados do projeto para um commit anterior/posterior especificado pelo seu codigo identificador

Em outras palavras, o commit que especificamos após o comando `git checkout` com seu codigo se torna o head temporariamente

- Para voltar para o estado normal utilizamos o comando `git checkout main` que faz o ultimo commit ser o head

- É possivel referenciar um commit N versões antes usado `~N`, por exemplo: 

`git checkout HEAD ~1`
`git checkout HEAD ~2`

### IMPORTANTE

Quando o git checkout for utilizado, os arquivos não podem ser alterados. Certifique-se de que os arquivos não foram alterados antes de voltar para o HEAD, pois as alterações cairão em um limbo, o que é considerado algo ruim que pode dar problema.

### Caso alguma alteração tenha sido feita sem querer
Desfaça as modificações

Podemos utilizar os seguintes comandos:

- `git reset`: Tira os arquivos da area de stage (caso tenha feito um git add por acidente)
- `git clean -df`:
- `git checkout -- .`: Esse checkout limpa modificações