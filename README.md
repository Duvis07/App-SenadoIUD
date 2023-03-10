# IUD-Diplomado-Senado-App

#Backend Java + Spring Boot - MySQL-JWT-JPA

# Proyecto Final Diplomado Web IU Digital

Pre-requisitos:
- El desarrollo de este proyecto se centra en el uso de Java con el framework spring boot, se usa la version de JDK 18
- Instalar Intellij IDEA , se aconseja la versión estable (17.0.5)
- Instalar la base de datos MySQL
- Instalar el gestor de base de datos (MySQL Workbench o PHPMyAdmin con XAMPP para correr el apache server) 
- Se recomienda configurar y descargar las librerías de spring boot (JPA, Lombox, MySQL Connector, Hibernate Validator , Spring boot Dev tools, Spring Security JSON Web Token, Model Mapper)
- Para realizar el consumo de la API Rest se usa el cliente Postman (version10.5.2 recomendada)

#Estudio de Caso
#Requerimientos
Se solicita la creación de un Backend en Java con Spring Boot de la App del senada
En la cual se pretende  registrar los proyectos propuestos en el Senado de la República. 

La aplicación debe ser capaz de registrar:
- Partidos políticos
- Senadores: Datos personas (id, nombres, departamento, partido)
- Proyectos: Id del proyecto (propio de la App), y demás datos


Debido a que el caso de estudio no es lo suficientemente claro se infiere que:


-Se deben crear 6 entidades en la Base de datos (Roles, Usuarios, PartidoPoliticos, Senadores, Proyectos, Votos) y deben tener las siguientes restricciones:

-Los Roles deben ser administrados por el SUPERADMIN es decir hacer la gestión desde la Base de datos.
-Los Usuarios, los Partidos políticos y los Senadores solo pueden ser creados, actualizados o eliminados por el Administrador 
-Los proyectos y los votos pueden ser gestionados por el usuario normal.

Es por ello que se presenta un arquitectura por Capas para el Desarrollo del software en la cual sobresalen los paquetes:
-Models : Clase donde se trabajan las Entidades hacia la BD
-Services : Es la Clase que nos ayuda con la conexión a los repositories (Se definen los métodos que un cliente puede utilizar)
-Repositories
-Controller: La capa que controla la aplicación, es decir, coordina la comunicacion entre las peticiones que se hacen desde un cliente, el modelo que procesa los datos
-Mappers:
-Config:
-Utilities:
-Exceptions:
-Security:
-DTO:

Carpeta de recursos:https://drive.google.com/drive/u/3/folders/1tTxLSmwyZVXPdhyE8dsCr-lbcaoH6ElY

Video de la aplicación funcionando: https://drive.google.com/drive/u/3/folders/1tTxLSmwyZVXPdhyE8dsCr-lbcaoH6ElY
