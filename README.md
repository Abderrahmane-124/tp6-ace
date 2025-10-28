# Système de Gestion des Étudiants

Une application API REST Spring Boot pour la gestion des dossiers étudiants.

## Technologies

- **Java 17**
- **Spring Boot 3.5.7**
- **Spring Data JPA**
- **MySQL**
- **Maven**
- **Swagger/OpenAPI** (SpringDoc)

## Fonctionnalités

- API RESTful pour la gestion des étudiants
- Validation des données
- Intégration avec base de données MySQL
- Documentation API avec Swagger UI
- Rechargement à chaud avec Spring Boot DevTools

## Prérequis

- JDK 17 ou supérieur
- Maven 3.6+
- MySQL 8.0+

## Installation

1. **Cloner le dépôt**
   ```bash
   git clone https://github.com/Abderrahmane-124/tp6-ace.git
   cd tp6-ace
    ```
## Configurer la base de données MySQL
Créer une base de données et mettre à jour src/main/resources/application.properties :
```
spring.datasource.url=jdbc:mysql://localhost:3306/student_db
spring.datasource.username=votre_nom_utilisateur
spring.datasource.password=votre_mot_de_passe
spring.jpa.hibernate.ddl-auto=update
```
## Compiler le projet
```
mvn clean install
```
## Lancer l'application
```
mvn spring-boot:run
```
L'application démarrera sur http://localhost:8080
## Documentation de l'API
Accéder à Swagger UI : http://localhost:8080/swagger-ui.html
## Structure du Projet
```
student-management/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── example/
│   │   │           └── studentmanagement/
│   │   │               ├── StudentManagementApplication.java
│   │   │               ├── controller/
│   │   │               │   └── StudentController.java
│   │   │               ├── model/
│   │   │               │   └── Student.java
│   │   │               ├── repository/
│   │   │               │   └── StudentRepository.java
│   │   │               └── service/
│   │   │                   ├── StudentService.java
│   │   │                   └── StudentServiceImpl.java
│   │   └── resources/
│   │       ├── application.properties
│   │       └── static/
│   │       └── templates/
│   └── test/
│       └── java/
│           └── com/
│               └── example/
│                   └── studentmanagement/
│                       └── StudentManagementApplicationTests.java
├── target/
├── .gitignore
├── pom.xml
├── mvnw
├── mvnw.cmd
└── README.md


```
## Auteur
Abderrahmane-124
# Captures d'ecran
<img width="1919" height="1199" alt="Screenshot 2025-10-27 202759" src="https://github.com/user-attachments/assets/5f5b9814-3270-479c-9faf-6167bfeeb30c" />

le screen si dessus montre que l'application run sans probleme




<img width="1919" height="1199" alt="Screenshot 2025-10-27 203545" src="https://github.com/user-attachments/assets/3d1cf2c1-6ef1-40de-b6cb-154457f8bba0" />
<img width="1919" height="1199" alt="Screenshot 2025-10-27 203628" src="https://github.com/user-attachments/assets/2e0ee2a5-00be-4de2-8f32-a7c83171db53" />
<img width="1919" height="1199" alt="Screenshot 2025-10-27 203923" src="https://github.com/user-attachments/assets/b3dce67f-aa84-413b-a83a-38179c8f2311" />
<img width="1919" height="1198" alt="Screenshot 2025-10-27 204045" src="https://github.com/user-attachments/assets/5a8c1b5d-6797-40a3-9c35-e534c8c8a5f2" />
<img width="1919" height="1199" alt="Screenshot 2025-10-27 204158" src="https://github.com/user-attachments/assets/4054e24f-7a8f-49ff-9bc3-9c89e2d1348d" />

les 5 screens si dessus demontrent le test des api's sur postman

<img width="1871" height="775" alt="Screenshot 2025-10-27 204606" src="https://github.com/user-attachments/assets/ffad8fd7-fd69-40fd-9dfa-f4e70b728548" />

le screen si dessus montre le resultat des tests unitaires

<img width="1919" height="1199" alt="Screenshot 2025-10-27 205213" src="https://github.com/user-attachments/assets/b14c6182-2734-4050-83a2-bd909479d63b" />

le screen si dessus inclus l'interface SWAGGER
