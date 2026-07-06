Esse arquivo vou compilar os princiais comandos par usar o git:

git --version
git init (inicia um repositório local vazio) - inicia no master
git add [arquivo] ( manda os arquivos para a área de stadding - basicammente os arquivos estão em um pré-commit)
git branch ( saber o nome da branch)
git branch -m master main (trocar o nome da branch)
git reset --soft HEAD~1 (desfaz o último commit, mas mantém o stage. Em seguida, fazer novo git add . e um novo commit)
git remote -v ( verificar a url)
git push origin main --force (força a substituição do histórioco remoto pelo local - tem consequencias - exclui todo o histórico)
