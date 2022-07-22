# Overview
This is a small Login & Sign up page created using below technologies-
1. python flask
2. HTML
3. SQlite3

## Required modueles
pip install flask

## Technical Details
- Database - `database/user_db.db`
- Table - `user_info`
- Table columns
    | Column Name | Datatype | Size | Primary Key | Not Null |
    | ----------- | -------- | ---- | ----------- | -------- |
    |name|char|1000|||
    |age|int||||
    |gender|char|1|||
    |contact_no|int||||
    |username|char|1000|Yes|Yes|
    |password|char|1000||Yes|
- `notebook-devlopment.ipynb` is testing jupyter notebook.

## Features
- Validate if username already exists in database while signup.
- Validate username and password while Login.

## How to execute
1. Execute `python app.py` to start server.
2. Once above command executes, it automatically creates database `database/user_db.db` and table `user_info`.
