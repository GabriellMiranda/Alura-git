=======
# Alura-git

## Lista de cursos para controlar o git

## Comandos Git
    -> Fazendo login no git:
        
        git config --local user.name "name"
        git config --local user.email "email"

    -> Iniciando repositório:

        git init

    -> Adcionar todos os arquivos para serem comitados:

        git add .

    -> Estatus dos arquivos:
    Verifica quais arquivos já foram comitados ou não

        git status

    -> Comitando na main:

        git commit -m "mensagem"

    -> informações git, verificação dos commits feitos, historio de commits:

        git log

    -> Para ignorar arquivos e não subilos para o repositorio, basta criar o arquivo:

        .gitignore/
            arquivos.

    -> Para atualizar as informações do seu repositório local: puxar os dados do git

        git pull origin master
        git pull <nome> <branch>

    -> Para empurrar as atulizações para o git:

        git push origin master
        git push <nome> <branch>

    -> Para saber a quantidade de branchs:

        git branch

    -> Para criar outra branch de desenvolvimento:

        git branch <nome_branch>

    -> Para acessar a outra branch:

        git checkout <nome_branch>

    -> Mergeando duas branches

        git merge <outra-branche>

    -> Desfazer uma alteração

        git checkout -- <nome_arquivo>

    -> commites e seus identificadores

        git log --oneline

    -> Navegando para outro commit

        git checkout <identificador_commit>

