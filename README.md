# comandosgit
comando reverter alteraçoes
git reset --soft <cod commit> retorna para o commit escolhido porem mantem as alteraçoes no repo local para um novo commit
git reset --mixed <cod commit> retorna para o commit escolhido porem mantem as alteraçoes no repo local e e necessario todo o processo de adicionar as alteraçoes
git reset --hard <cod commit> retorna para o commit escolhido e apaga todas as alteraçoes feitas apos este commit

comando
git diff  mostra o que realmente foi alterado no repo local
git diff --name-only mostra o nome dos arquivos que foram modificados
git diff <nome do arquivo escolhido>

git checkout HEAD -- <nome do arquivo que voltara estado original da branch>
