# Workshop - JavaFX JDBC

This project was developed as a workshop during the *"Java COMPLETO 2023 Programação Orientada a Objetos + Projetos"* course by Professor Nelio Alves, available on [Udemy](https://www.udemy.com/course/java-curso-completo/).

It was created as a platform for testing and experimenting with JavaFX and JDBC. This application implements a simple CRUD system that manages sellers and departments with a visual interface, simulating the kind of system a real-world company might employ.

# Setting it up

Before you begin, ensure that you have all the requirements installed on your machine.

First, within the project files, you will find a file named `database.sql` containing the commands to generate the tables and mock data that will be used. Additionally, there is a file named `properties.db`, responsible for enabling Java to access your database.

### Database Configuration

1. Open MySQLWorkbench and create a new connection.
2. Follow the details provided in the properties file mentioned above and complete the setup.
3. If you prefer not to create a new connection, make sure to adjust the data in the properties file to match your existing connection. Please note that it is case-sensitive, so take your time when configuring it.

### Database Setup

With the database connection established and the properties matching, you can proceed to create a new database. If you want to use the properties file as a reference, execute the following query: `CREATE DATABASE coursejdbc` and run it. This will create a new database named 'coursejdbc,' which we will be using.
 
Open the database by double-clicking it and then run a new query using the commands found inside the `database.sql` file to set up the tables and mock data.

Now, the application should be ready to run. If you encounter any errors related to JavaFX, make sure to refer back to its documentation, which is listed below, and check if you have followed all the instructions as stated there. Be sure to also follow the instructions for your IDE.


# Demo

![demo1](https://raw.githubusercontent.com/AlysonCantalice/workshop-javafx-jdbc/main/images/demo1.png)

![demo2](https://raw.githubusercontent.com/AlysonCantalice/workshop-javafx-jdbc/main/images/demo2.png)

![demo3](https://raw.githubusercontent.com/AlysonCantalice/workshop-javafx-jdbc/main/images/demo3.png)

![demo4](https://raw.githubusercontent.com/AlysonCantalice/workshop-javafx-jdbc/main/images/demo4.png)

# Requirements

To run this project, it's necessary to have Java 17 (LTS) installed on your machine. The Java version I used was Java Azul Zulu 17.0.7 (LTS) ([link](https://www.azul.com/downloads/?version=java-17-lts&package=jdk#zulu)), but it should not be necessary to have this exact version for the project to work.

As we have to work with databases, you'll need to have **MySQL** and **MySQLWorkbench** installed and running on your computer.

As this is a graphical application using **JavaFX** ([link](https://gluonhq.com/products/javafx/)), we will need to install this library. Follow this documentation with further instructions on how to properly install it. [Getting Started with JavaFX](https://openjfx.io/openjfx-docs/).

##

Created by @AlysonCantalice.
