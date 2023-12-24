# FastAPI & Mongo-DB Setup Manual

**Project Description:**

Created API's for an online bookstore that enables users to perform CRUD(Create/Add, Read/View, Update, Delete books) operations and many more. User can browse, view the list of books, get information about the top selling books and authors, check for total number of books, and retrieve a specific book. We have also implemented the aggregation operations of MongoDB to filter the top 5 best selling books and authors. FastAPI will be used to build the API, and MongoDB will be used to store the book data.


**Steps to run the API:**

1. create a virtual environment

    python -m venv venv

2. Enter virtual environment

    windows: venv\Scripts\activate
    
    linux: venv/bin/activate
    
    mac: source env/bin/activate

3. Install requirements

    pip install -r requirements.txt

4. Set up mongoDB create database and collection

    run python mongo.py

5. Install MongoDB and open MongoDB Compass (or any client)
    
    Create a database and add collections.
    
    Import the JSON/CSV files in respective collection.

5. Run the main file to start api

    uvicorn main:app --reload


