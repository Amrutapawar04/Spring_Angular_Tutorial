# Spring Boot + Angular 15 + PostgreSQL example: CRUD App

We will build a full-stack Angular 15 and Spring Boot PostgreSQL CRUD Tutorial Application in that:
* Each Tutorial has id, title, description, published status.
* We can create, retrieve, update, delete Tutorials.
* We can also find Tutorials by title.

## The images below shows screenshots of our System.

**– Add Tutorial:**
**– Retrieve Tutorials:**
**– Click on Edit button to go to a Tutorial page:**
**On this Page, you can:**

* change status to Published using Publish button
* delete the Tutorial using Delete button
* update the Tutorial details with Update button

**– Search Tutorials by title:**

**– PostgreSQL database table looks like this:**


### Technology

The things you need before installing the software.

* Java 17 / 11 / 8
* Spring Boot 3 / 2 (with Spring Web MVC, Spring Data JPA)
* PostgreSQL
* Maven
* Angular 15
* Angular HttpClient
* Angular Router
* Bootstrap 4

### Project Structure

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


