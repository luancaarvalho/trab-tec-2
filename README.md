# Trab tec 2


O projeto é um exemplo de aplicação com Spring Boot + JPA + Rest + H2 + Swagger.

1. Spring Boot
2. JPA
3. Rest Controller
4. H2
5. Swagger

Ele consiste em um crud Spring de um gerenciamento de comida e suas calorias.
Para acessar a Ui, a qual, somente lista as comidas que existem no banco H2, basta ir a url
http://localhost:8080/calTracking e fazer as requisições para as rotas da api que estao no arquivo calorieTracking-endpoints.json

#Build

O build foi feito através do gerenciador de dependências Maven, único e exclousivamente com ele.
Como o banco da aplicação é um h2, ele reseta a cada interaçõ e nao foi preciso subir um docker ou coisa semelhante.

#CI

O CI do projeto foi feito através do Github Actions, o qual conecta-se com o repositório através da sua integração com projetos Java maven
