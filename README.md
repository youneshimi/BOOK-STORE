# Book Store CRUD Application

<img src="https://www.oracle.com/a/ocom/img/cb71-java-logo.png" alt="Java Logo" width="100" height="100"/> <img src="https://logodix.com/logo/1614292.png" alt="Spring Boot Logo" width="100" height="100"/>

Bienvenue dans l'application Book Store, une application CRUD développée avec Java et Spring Boot, avec une base de données MySQL.

## Prérequis

Assurez-vous d'avoir les éléments suivants installés avant de démarrer l'application :
- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/javase-downloads.html)
- [Spring Boot](https://spring.io/projects/spring-boot)
- [MySQL Database](https://www.mysql.com/)

## Configuration de la base de données

1. Créez une base de données MySQL appelée `bookstore`.
2. Configurez les paramètres de connexion dans le fichier `application.properties` :

```properties
spring.datasource.url=jdbc:mysql://localhost:1001/bookstore
spring.datasource.username=votre_nom_utilisateur
spring.datasource.password=votre_mot_de_passe
