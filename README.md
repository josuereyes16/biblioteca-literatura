
## LiterALURA library / Biblioteca LiterALURA → [josuereyes16](https://github.com/josuereyes16)

| Description | Descripcion |
|---------|---------|
| LiterAlura is a console application developed in Java, using Spring Boot and PostgreSQL, designed to manage a book catalog. It allows users to search and register books in a database through an API, list books and registered authors, filter authors alive in a specific year, and classify books by language. | LiterAlura es una aplicación de consola desarrollada en Java, utilizando Spring Boot y PostgreSQL, diseñada para gestionar un catálogo de libros. Permite a los usuarios buscar y registrar libros en una base de datos a través de una API, listar libros y autores registrados, filtrar autores vivos en un año específico y clasificar libros por idioma.|

---

| Features | Características |
|---------|---------|
| - Search book by title: Allows searching for books by title in the API and registering them in the database. | - Buscar libro por título: Permite buscar libros por su título en la API y registrarlos en la base de datos.
| - List registered books: Displays all books registered in the database. | - Listar libros registrados: Muestra todos los libros registrados en la base de datos.
| - List registered authors: Displays all authors registered in the database. | - Listar autores registrados: Muestra todos los autores registrados en la base de datos.
| - List living authors in a specific year: Allows filtering authors who were alive in a specific year. | - Listar autores vivos en un año específico: Permite filtrar autores que estaban vivos en un año determinado.
| - List books by language: Classifies registered books by language. | - Listar libros por idioma: Clasifica los libros registrados por idioma.


---

| Installation | Instalación |
|---------|---------|
| Clone the repository: `git clone https://github.com/josuereyes16/biblioteca-literatura.git` | Clonar el repositorio: `git clone https://github.com/josuereyes16/biblioteca-literatura.git`|
| Navigate to the project directory: `cd literalura` | Navegue al directorio del proyecto: `cd literalura`|
|Create a project in Spring Initializr: | Crear un proyecto en Spring Initializr:
| `Visit start.spring.io.` <br> `Select Maven, Java, and the latest version of Spring Boot.` <br> `Add dependencies: Spring Data JPA and PostgreSQL Driver.` | `Visite start.spring.io.` <br> `Seleccione Maven, Java y la última versión de Spring Boot.` <br> `Agregue dependencias: Spring Data JPA y el controlador PostgreSQL.`
| Import the project into your preferred IDE. | Importe el proyecto a su IDE preferido.
| Configure the database in application.properties: | Configure la base de datos en application.properties:
| `spring.datasource.url=jdbc:postgresql://localhost:5432/database_name` <br> `spring.datasource.username=username` <br> `spring.datasource.password=password` <br>  `spring.jpa.hibernate.ddl-auto=update`  | `spring.datasource.url=jdbc:postgresql://localhost:5432/database_name` <br> `spring.datasource.username=nombre de usuario` <br> `spring.datasource.password=contraseña` <br> `spring.jpa .hibernate.ddl-auto=actualizar`                       
| Run the application: `./mvnw spring-boot:run` | Ejecute la aplicación: `./mvnw spring-boot:run`

---

| Contribution | Contribuciones |
|---------|---------|
| Fork the repository. | Bifurca el repositorio. |
| Create a new branch: `git checkout -b feature/new-feature` |  Crea una nueva rama: `git checkout -b feature/new-feature` |
| Make changes and commit them: `git commit -m "Add new feature"` |  Realice cambios y confírmelos: `git commit -m "Agregar nueva característica"` |
| Push the changes to the remote repository: `git push origin feature/new-feature` |  Envíe los cambios al repositorio remoto: `git push origin feature/new-feature` |
| Create a Pull Request on GitHub. |Cree una solicitud de extracción en GitHub. |

----

| Usage | Uso |
|---------|---------|
| Search for books by title in the API and register them in the database. | Busque libros por título en la API y regístrelos en la base de datos. |
| List registered books and authors.  | Lista de libros y autores registrados. |
| Filter living authors in a specific year.  | Filtrar autores vivos en un año específico. |
| Classify books by language. | Clasificar libros por idioma.  | 

