# Criando-Repositorio-No-GIT

Como Versionar um Projeto através de um Repositório, que em seu Computador, basicamente, será uma pasta que terá todos os arquivos do seu projeto.

`$ git init`

Este comando, irá criar uma pasta `.git` na raiz do projeto e nela, ficarão registradas as informações relacionadas ao controle do versionamento.

*Conectar um repositório local com a nuvem do GitHub*

Se você já está trabalhando em um projeto que ainda não está versionado, você pode criar um repositório no GitHub e conectar seus arquivos locais com o GitHub. Para adicionar o rastreamento remoto, use o comando `git remote add` no terminal, no diretório em que seu repositório está armazenado.

`/* navegando até a pasta / $ cd nomedaminhapasta / estando dentro da pasta do projeto, indique a URL / $ git remote add origin https://github.com/user/repo.git / verificando a origem adicionada ao repositório / $ git remote -v / Retorno esperado */ origin https://github.com/user/repo.git (fetch) origin https://github.com/user/repo.git (push)`
