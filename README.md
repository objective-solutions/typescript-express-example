# Como rodar essa aplicação

1. Rodar `yarn install`
2. Rodar `docker run -p 3306:3306 -e MYSQL_ROOT_PASSWORD=test -e MYSQL_DATABASE=test -e MYSQL_USER=test -e MYSQL_PASSWORD=test -d mariadb:5.5`
3. Rodar `yarn typeorm migration:run`
4. Você pode acessar `http://localhost:3000/posts` para ver uma lista vazia
5. Você pode usar curl, postman ou qualquer outra ferramenta para testar
