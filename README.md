#bkpmysqlviaphp
Executa o Backup do banco de dados mysql diretamento pelo painel adm do site

Necessário alterar a linha -> require('./_app/Config.inc.php'); <- no arquivo index.php para o seu arquivo de conexão com o banco.         
Se for usar o sistema em seu painel já pronto, verificar também as constantes na linha -> $conn = mysqli_connect(HOST, USER, PASS, DBSA); <-

Caso for usar o arquivo de conexão da pasta _app/Config.inc.php, basta colocar os dados do seu banco de dados mysql.

Ao executar o backup, será criada uma pasta chamada backup na mesma pasta aonde está o index.php deste sistema com um arquivo SQL.
