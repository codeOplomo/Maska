## SPRING FRAMEWORK

This application is a basic User Management System
built using Spring Core without Spring Boot,
Spring MVC, and Spring Data JPA. It allows users to perform CRUD operations
such as creating, viewing, updating, and deleting users through a web interface.

## Table of Contents
- [Project Structure](#project-structure)
- [Dependency Injection (DI)](#dependency-injection-di)
- [Inversion of Control (IoC)](#inversion-of-control-ioc)
- [Spring Beans](#spring-beans)
- [Bean Scopes](#bean-scopes)
- [ApplicationContext](#applicationcontext)
- [Component Scanning and Stereotype Annotations](#component-scanning-and-stereotype-annotations)
- [Spring Data JPA](#spring-data-jpa)
- [Spring MVC](#spring-mvc)
- [Installation and Setup](#installation-and-setup)

### Project Structure
```
Maska-main
├── .idea
├── .smarttomcat
├── src
│   ├── main
│   │   ├── java
│   │   │   └── org.example
│   │   │       ├── controller
│   │   │       │   ├── HomeController
│   │   │       │   └── MembreController
│   │   │       ├── model
│   │   │       │   └── Membre
│   │   │       ├── repository
│   │   │       │   └── MembreRepository
│   │   │       └── services
│   │   │           └── MembreService
│   │   └── webapp
│   │       └── WEB-INF
│   │           ├── applicationContext.xml
│   │           ├── dispatcher-servlet.xml
│   │           └── web.xml
└── webapp
    └── WEB-INF
        └── views
```
### Dependency Injection (DI)

La dépendance injection (DI) est un modèle de conception logicielle qui permet d'atteindre l'Inversion de Contrôle (IoC) entre les classes et leurs dépendances. En termes simples, DI permet à un objet de recevoir d'autres objets dont il dépend, au lieu de les créer directement. Cela rend le code plus modulaire, flexible et facile à tester.

### Inversion of Control (IoC)

L'inversion de contrôle (IoC) est un principe de programmation qui renverse le flux de contrôle dans un programme, transférant la responsabilité de gestion des dépendances et des processus d'une classe vers une entité externe. Au lieu qu'une classe contrôle directement ses dépendances ou son flux de processus, cette responsabilité est déléguée à un framework, un conteneur ou une entité de niveau supérieur.

### Spring Beans

Dans le framework Spring, un bean est un objet qui est instancié, assemblé et géré par le conteneur IoC (Inversion of Control) de Spring. Les beans Spring sont la base d'une application Spring et sont essentiels pour gérer le cycle de vie et les dépendances des objets.

### Bean Scopes                                                                                                     

Dans Spring, les bean scopes définissent le cycle de vie et la visibilité d'un bean au sein du contexte de l'application. La portée détermine combien de temps un bean sera actif et comment il sera partagé entre les clients.

### ApplicationContext

Dans Spring, l'ApplicationContext est une interface centrale qui fournit la configuration et la gestion des beans dans une application Spring. C'est une extension du BeanFactory et elle ajoute plusieurs fonctionnalités pour supporter des applications plus complexes.

### Component Scanning and Stereotype Annotations                                                                                                
La détection de composants (component scanning) et les annotations stéréotypes (stereotype annotations) sont des éléments intégrés du mécanisme d'injection de dépendances et de gestion des beans de Spring. Elles simplifient le processus de configuration, améliorent la modularité des applications et clarifient le code en définissant clairement les rôles des différents composants. En tirant parti de ces fonctionnalités, les développeurs peuvent créer des applications Spring plus propres, plus maintenables et facilement testables.

### Spring Data JPA

Spring Data JPA est un projet de Spring qui simplifie l'interaction avec les bases de données en utilisant la technologie Java Persistence API (JPA). Il permet aux développeurs de travailler avec des bases de données relationnelles de manière plus fluide et intuitive, en minimisant le besoin d'écrire du code de persistance répétitif. Voici un aperçu des principales caractéristiques et fonctionnalités de Spring Data JPA.

### Spring MVC

Spring MVC est un module du framework Spring qui facilite le développement d'applications web basées sur le modèle MVC (Modèle-Vue-Contrôleur). Il fournit une structure robuste et flexible pour créer des applications web en séparant les préoccupations liées à la présentation, à la logique métier et à la gestion des données. Voici un aperçu des principales caractéristiques et concepts de Spring MVC.                                                                                                                                                                                                                                                 
  
