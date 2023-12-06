# Como deletar commits junto com as modificações nos arquivos

As ações a seguir fazem o projeto voltar ao estado de um determinado commit

Para fazer isso, utilizamos o comando `git reset --hard <codigo do commit>`. Este comando permite que você exclua modificações até certo commit especificado, excluindo varias modificações ques estão a frente desse. Muito util quando você faz besteira no projeto e precisa voltar para uma versão instavel.

Se você quiser voltar especificamente para o penúltimo commit, utilize o comando `git reset --hard HEAD~1`. O que este comando faz, é apagar o commit atual, ou seja, volta um commit atrás.