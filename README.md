# AirBnB clone - MySQL

> This directory contains all the tasks of the project "0x02. AirBnB clone - MySQL" at [ALX](https://www.alxafrica.com/ "ALX.")



## Table of Contents

- [AirBnB clone - MySQL](#airbnb-clone---mysql)
  - [Table of Contents](#table-of-contents)
  - [Project General Objectives](#project-general-objectives)
  - [Project Description](#project-description)
  - [Directory Files Description](#directory-files-description)
  - [Prerequisites](#prerequisites)
  - [AUTHORS](#authors)
 

## Project General Objectives

* What is Unit testing and how to implement it in a large project.
* What is *args and how to use it.
* What is **kwargs and how to use it.
* How to handle named arguments in a function.
* How to create a MySQL database.
* How to create a MySQL user and grant it privileges.
* What ORM means.
* How to map a Python Class to a MySQL table.
* How to handle 2 different storage engines with the same codebase.
* How to use environment variables.

## Project Description

The Airbnb clone is one of the main projects at Holberton School, it's a long term project that we need to accomplish by building up trough a series of small modules or pieces. This project is thinking as a whole for a software developer, to learn and become a full-stack developer, gluing alltogether the infrastructure of the Airbnb from back to front, including databases, static and dynamic content, web frameworks, APIs, and web infrastructure.
The first step that we need to build is "the console" or the command interpreter, this is meant to be a tool to validate or manipulate the storage system, through the console we are gonna be able of:
* Create our data model.
* Manage (create, update, destroy, etc) objects.
* Store and persist objects to a file (JSON file)

This storage engine will give us an abstraction between “My object” and “How they are stored and persisted”.

You can find this in: [AirBnB clone - The console](https://github.com/luismvargasg/AirBnB_clone)

For the second part of the project we should build the database connection through SQLAlchemy, the ORM of Python.

Using a MySQL storage we replace the file storage (JSON file) by a Database storage and we map your models to a table in database by using an O.R.M.

## Directory Files Description

| **File** | **Description** |
|----------|-----------------|
| [Console](./console.py) | Program that contains the entry point of the command interpreter. |
| [MySQL setup dev file](./setup_mysql_dev.sql) | Script that prepares a MySQL server for the project. |
| [MySQL setup test file](./setup_mysql_test.sql) | Script that prepares a MySQL server for the project. |
| [Engine DBStorage](./models/engine/db_storage.py) | Module that serializes instances in a JSON file and deserializes JSON file to instances. |
| [File Storage](./models/engine/db_storage.py) | Module that serializes instances in a JSON file and deserializes JSON file to instances. |
| [BaseModel](./models/base_model.py) | Class BaseModel that defines all common attributes/methods for other classes. |
| [City](./models/city.py) | File that contains the City class that inherit from BaseModel. |
| [State](./models/state.py) | File that contains the State class that inherit from BaseModel. |
| [User](./models/user.py) | File that contains the User class that inherit from BaseModel. |
| [Place](./models/place.py) | File that contains the Place class that inherit from BaseModel. |
| [Review](./models/review.py) | File that contains the Review class that inherit from BaseModel. |
| [Amenity](./models/amenity.py) | File that contains the Amenity class that inherit from BaseModel. |
| [init file](./models/__init__.py) | File that defines a Python Package. |
| [AUTHORS](./AUTHORS) | File that contains the AUTHORS of this project. |
| [TESTS](./tests) | Directory that contains all the Unittest files to test the different classes and methods. |





## AUTHORS

**Alfredo Kalu Orie**
**Ojieide Egbomondion**

* [Github @xclusivfred](https://github.com/xclusivfred)
* [Github @Ojieide](https://github.com/Ojieide)
