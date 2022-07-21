# Overview
This is a small Login & Sign up page created using below technologies - 
1. python flask
2. HTML
3. SQlite3

## Required modueles
pip install flask

## How to execute
1. Execute `python app.py` to start server.
2. Once above command executes, it automatically creates database `database/user_db.db` and table `user_info`.
3. `username` is primary key and it will be unique. This project is able to validate if `username` already exits in database or not while signup.
4. `notebook-devlopment.ipynb` is testing jupyter notebook.
5. Table `user_info` has below columns
    - name char(1000)
    - age int
    - gender char(1)
    - contact_no int
    - username char(1000) [primary key] [not null]
    - password char(1000) [not null]