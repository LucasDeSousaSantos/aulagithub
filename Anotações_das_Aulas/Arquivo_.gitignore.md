# Arquivo .git.gnore

O arquivo ***.gitignore*** é um arquivo que indica o que *NÃO* deve ser salvo pelo Git.

Existem arquivos que não dever ser salvos, portanto eles devem ser especificados em um outro arquivo chamado ***.gitignore***

Podemos encontrar este aquivo na pasta principal do repositorio, mas também é possivel colocalos em sub-pastas dentro do repositorio para indicar o que deverá ser ignorado em cada subpasta. Isso ocorre muito quando temos mais de um projeto em um mesmo repositorio.

### Casos comuns de arquivos que não devem ser salvos pelos git

- Arquivos compilados: Arquivos Java, C, C++, C#...
- Arquivos de bibliotecas externas usadas no projeto: Projetos reais utilizam bibliotecas externas (que são um conjunto de programas prontos disponíveis na internet). Essses arquivos não precisam ser salvos, pois se outra pessoa fizer download do seu projeto, o gerenciador de dependencias do computador dessa pessoa se incarregará de baixar as bibliotecas nescessarias (utilizadas no projeto).
- Arquivos de configuração da sua IDE: .vscode (subpasta de configurações)
- Arquivos de configuração do sistema