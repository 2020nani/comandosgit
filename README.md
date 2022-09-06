# comandosgit
comando reset alteraçoes
git reset --soft <cod commit> retorna para o commit escolhido porem mantem as alteraçoes no repo local para um novo commit
git reset --mixed <cod commit> retorna para o commit escolhido porem mantem as alteraçoes no repo local e e necessario todo o processo de adicionar as alteraçoes
git reset --hard <cod commit> retorna para o commit escolhido e apaga todas as alteraçoes feitas apos este commit

git revert --no-edit <codigo do commit que sera revertido> reverte as aleraçoes que subiram no commit porem nao exclui o commit da arvore do git

comando
git diff  mostra o que realmente foi alterado no repo local
git diff --name-only mostra o nome dos arquivos que foram modificados
git diff <nome do arquivo escolhido>

git checkout HEAD -- <nome do arquivo que voltara estado original da branch>

git fetch  puxa as alteraçoes realizadass no repo remoto

teste 2

git push origin :<nome branch,tag... a ser deletada remoto>

git branch -D nome da branch local a ser deletada

puxar alteraçoes do repo remoto para repo local
git pull <branch remoto> <branch local>

erro aqui