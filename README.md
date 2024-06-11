# FruityLoops

FruityLoops is a simple Spring Boot application that demonstrates the use of JSP and JSTL for rendering a list of items dynamically. This project focuses on practicing the setup of dependencies and imports for JSP and JSTL, reviewing OOP concepts, and using the `c:forEach` JSTL tag to render lists in JSP.

## Introduction

This project is a simple web application that displays a list of fruits and their prices. It uses Spring Boot for the backend and JSP with JSTL for the frontend. The application showcases the following concepts:

- Setting up dependencies and imports for using JSP and JSTL in a Spring project.
- Reviewing OOP concepts.
- Accessing member variables of an object instance from within a JSP file.
- Using the `c:forEach` JSTL tag to render lists.

## Explanation of Files

- **Item.java:** The model class representing an item with a name and price.
- **ItemController.java:** The controller that handles requests to the root URL and passes a list of fruits to the view.
- **index.jsp:** The JSP file located in `src/main/resources/templates` that renders the list of fruits and their prices using the `c:forEach` JSTL tag.
- **application.properties:** Configuration file for the Spring Boot application.
- **pom.xml:** Maven configuration file that includes dependencies for Spring Boot, JSP, and JSTL.

