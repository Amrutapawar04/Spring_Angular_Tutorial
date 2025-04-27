# Spring Boot + Angular 17 + PostgreSQL example: CRUD App

We will build a full-stack Angular 17 and Spring Boot PostgreSQL CRUD Tutorial Application in that:
* Each Tutorial has id, title, description, published status.
* We can create, retrieve, update, delete Tutorials.
* We can also find Tutorials by title.

## The images below shows screenshots of our System.

**– Add Tutorial:**

![add 1](https://github.com/user-attachments/assets/76c876e1-55db-48f9-9e90-8bec89caa67e)

**– Retrieve Tutorials:**
![edit](https://github.com/user-attachments/assets/45cc58e4-fbc2-4c58-9455-63a10842e9f8)


**– Click on Edit button to go to a Tutorial page:**
**On this Page, you can:**
![update](https://github.com/user-attachments/assets/1c22174d-a402-47e3-8001-48881ce33cab)

* change status to Published using Publish button
* delete the Tutorial using Delete button
* update the Tutorial details with Update button

**– Search Tutorials by title:**
![home page ](https://github.com/user-attachments/assets/cc2608dc-b0a3-4a01-9077-278d329dd72c)




### Technology

The things you need before installing the software.

* Java 17 
* Spring Boot 3 (with Spring Web MVC, Spring Data JPA)
* PostgreSQL
* Maven
* Angular 17
* Angular HttpClient
* Angular Router
* Bootstrap 4

### Project Structure

![Screenshot 2025-04-27 130825](https://github.com/user-attachments/assets/f2535010-a9b8-4aa2-85cc-0e277fc1b22b)

A step by step guide that will tell you how to get the development environment up and running.


$ -tutorial.model.ts exports the main class model: Tutorial.
$ – There are 3 components: tutorials-list, tutorial-details, add-tutorial.
$ – tutorial.service has methods for sending HTTP requests to the Apis.
$ – app-routing.module.ts defines routes for each component.
$ – app component contains router view and navigation bar.
$ – app.module.ts declares Angular components and import necessary modu



## Deployment
You can run this App with command: les.
```ng serve --port 8081.
If the process is successful, open Browser with ``Url: http://localhost:8081/ and check it.


