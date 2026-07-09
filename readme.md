Esse arquivo vou compilar os princiais comandos par usar o git:

git --version   

git init (inicia um repositório local vazio) - inicia no master
git add [arquivo] ( manda os arquivos para a área de stadding - basicammente os arquivos estão em um pré-commit)

git branch (saber o nome da branch)
git branch nome (cria uma branch chamada nome)
git branch -m master main (trocar o nome da branch)
git branch -a (verifica quais branchs são locais ou remotas)

git reset --soft HEAD~1 (desfaz o último commit, mas mantém o stage. Em seguida, fazer novo git add . e um novo commit)
git remote -v ( verificar a url)

git push origin main --force (força a substituição do histórioco remoto pelo local - tem consequencias - exclui todo o histórico)

git stash (salva temporariamente aterações que ainda não precisam ser commitadas, podendo alterar de branch)

git checkout nome (vai diretamente para a branch "nome")
git checkout -b nome (cria uma branch nova chamada "nome" a partir da branch atual e já faz o checkout automático)

git restore .(Desfaça todas as alterações que ainda não foram commitadas e volte os arquivos para o estado do último commit.")

git merge branch ("Pegue todos os commits que existem na branch formatacao-prettier e ainda não existem na branch atual (main) e incorpore-os." - depois, deve ser feito o git push origin main)

