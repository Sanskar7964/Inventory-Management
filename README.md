Tech Stack

* Spring Boot
* Thymeleaf
* MySQL
* Hibernat

Instructions to install and run:
* Clone the repo and open it on an ide like eclipse.
* Clean and Rebuild the Project :
                Clean the Project:

                    In Eclipse/STS, right-click on the project and select Maven > Update Project with Force Update of Snapshots/Releases checked.
                    Right-click on the project and select Maven > Clean.

 * Rebuild the Project:

    Right-click on the project and select Run As > Maven install.

 * Run the Application:

      Right-click on the main application class and select Run As > Spring Boot App.

   Project Structure
   Spring Boot:
   src
├── main
│   ├── java
│   │   └── com
│   │       └── example
│   │           └── demo
│   │               ├── MySpringBootApplication.java
│   │               ├── YourEntity.java
│   │               └── YourRepository.java
│   ├── resources
│       └── application.properties
└── pom.xml
Static front end:
src
└── main
    └── resources
        └── static
            ├── css
            │   └── style.css
            ├── js
            │   └── script.js
            └── images
                └── logo.png
   Thymeleaf:
   src
└── main
    └── resources
        └── templates
            ├── index.html
            └── about.html

