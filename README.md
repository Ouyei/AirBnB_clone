# In this repository we carry out the projets AirBnb Clone

## description of the project:

In this project we will develop a clone of the AirBnb app.
This application is responsible for making accommodation offers
through which customers can publish and hire hosting.
It will be a teamwork of two people and is divided into
different parts, this is the first, which consists in the development
from the console.

## description of the command interpreter:

In this case, we want to be able to manage the objects of our project:

- Create a new object (ex: a new User or a new Place)
- Retrieve an object from a file, a database etc…
- Do operations on objects (count, compute stats, etc…)
- Update attributes of an object
- Destroy an object

## First step: we need to write a shell to manage your AirBnB objects.

This is the first step in creating our first full web application: the AirBnB clone. This first step is very important because you will be using what we build during this project with all the other projects below: HTML/CSS templates, database storage, APIs, front-end integration...

Each task is linked and will help us:

- set a main class (called BaseModel) to take care of the initialization, serialization and deserialization of its future instances
- create a simple serialize/deserialize flow: Instance <-> Dictionary <-> JSON string <-> file
- create all classes used for AirBnB (User, State, City, Place...) that inherit from BaseModel
- create the project's first abstract storage engine: file storage.
- create all the unit tests to validate all our classes and storage engine

## Requirements
Python Scripts

- Allowed editors: vi, vim, emacs
- All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
- All your files should end with a new line
- The first line of all your files should be exactly #!/usr/bin/python3
- A README.md file, at the root of the folder of the project, is mandatory
- Your code should use the pycodestyle (version 2.7.*)
- All your files must be executable
- The length of your files will be tested using wc
- All your modules should have a documentation (python3 -c 'print(__import__("my_module").__doc__)')
- All your classes should have a documentation (python3 -c 'print(__import__("my_module").MyClass.__doc__)')
- All your functions (inside and outside a class) should have a documentation (python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')
- A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)

Python Unit Tests
- Allowed editors: vi, vim, emacs
- All your files should end with a new line
- All your test files should be inside a folder tests
- You have to use the unittest module
- All your test files should be python files (extension: .py)
- All your test files and folders should start by test_
- Your file organization in the tests folder should be the same as your project
e.g., For models/base_model.py, unit tests must be in: tests/test_models/test_base_model.py
e.g., For models/user.py, unit tests must be in: tests/test_models/test_user.py
- All your tests should be executed by using this command: python3 -m unittest discover tests
- You can also test file by file by using this command: python3 -m unittest tests/test_models/test_base_model.py
- All your modules should have a documentation (python3 -c 'print(__import__("my_module").__doc__)')
- All your classes should have a documentation (python3 -c 'print(__import__("my_module").MyClass.__doc__)')
- All your functions (inside and outside a class) should have a documentation (python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')
- We strongly encourage you to work together on test cases, so that you don’t miss any edge case

## Authors:

- Oscar Bedat
- Marco Sózaro


