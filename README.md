# DS Catalog
O DS Catalog consiste em um sistema de catálogo de produtos, nele existe três tipos de permissões, a do usuário não autenticado, que pode somente visualizar os produtos, a do usuário com perfil operador, que pode também adicionar categorias ou produtos e a do usuário administrador, que além das outras permissões, também pode controlar os outros usuários da aplicação. A relação entre produtos e categorias é N-1. Ou seja, um produto pode ter uma ou várias categorias

# Modelo conceitual

<div align="center">
<img src="https://github.com/CarlosDaniel396/dscatalog-devsuperior/blob/main/assets/modelo-conceitual.png"/>
</div>


# Tecnologias utilizadas
* Java
* Spring Boot
* JPA / Hibernate
* Maven
* JUnit
* Postgresql

# Implantação em produção
* Back end: Heroku

# Como rodar o projeto

Pré-requisitos: Java 11
```
# Clonar repositório
git clone https://github.com/CarlosDaniel396/dscatalog-devsuperior.git

# Entrar na pasta backend
cd backend

# executar o projeto
./mvnw spring-boot:run

```
# Autor
Carlos Daniel Oliveira Nunes

www.linkedin.com/in/carlos-daniel27
