The api has following requests : 
    1. post 
    2.get
    3.update (put)
    4.delete 

A connection is made to the postgres sql and sql alchemy is used to avoid writing queries.
A pydantic model is created which as of now lacks validation, but generates a class to be used by the fastapi import.
Another model is created in the database_model file in which a class is created which is used by the database to make its column.
