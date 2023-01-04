# Comandos Git
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
    
    git add .gitignore