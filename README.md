# Tutorial

1 - Execute o dump.sql no PostgreSQL

2 - Descompacte o arquivo "candidatos.tar.gz":

```
tar -xvf candidatos.tar.gz
```
3 - Compile e execute o arquivo "Main.java":

```
javac Main.java && java Main
```

Feito isso, é necessário informar a URL do banco de dados, o usuário, a senha e o diretório em que se encontra os arquivos dos candidatos.
Segue o exemplo abaixo:

```
 _____ ____  _____       _ _     
|_   _/ ___|| ____|   __| | |__  
  | | \___ \|  _|    / _` | '_ \ 
  | |  ___) | |___  | (_| | |_) |
  |_| |____/|_____|  \__,_|_.__/

Banco de Dados(URL): localhost/tse
Usuário: postgres
Senha: postgres
Digite o caminho para o diretório dos candidatos: /home/vaz/tse-db/candidatos/ 
```
