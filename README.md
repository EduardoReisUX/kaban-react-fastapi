# Kanban - Full Application in React and FastAPI  


>This full stack application consists in a Kanban Board using **React**, **FastAPI** and **PosgreSQL**.

The app is able to make a user authentication and each user has their own
board which is saved on the database. More importantly it has the feature of drag an drop, 
allowing to create columns and tasks. As a result, it's extremely customizable.

## DEMO

![kaban-board-print](https://user-images.githubusercontent.com/39144691/149261465-e5e53b98-40a6-44ea-976f-32fa3cf7557f.png)

<img src="https://i.giphy.com/d8R6hPfMI1aTldwIsr.gif" width="660">


### REST API Swagger Docs With FastAPI


![rest_api_fastapi](https://user-images.githubusercontent.com/39144691/149065446-35a44954-5a80-441d-a094-0b66aa338bb4.png)


### Extensions used on the Backend:

**FastAPI**

**Tortoise-ORM**

**Uvicorn**

PyJWT

Pydantic

- DB: **Postgres** + Adminer with Docker

The requirements file show everything you need to run it

### Libraries/frameworks used on the FrontEnd

**React**

React-dom

React-router-dom

Style-components

Other can be seen on the package.json file


##Usage 

Initiate backend

 uvicorn main:app --reload 


### Credits

The core of the application
was done following the tutorial by the
[Pretty Printed](https://www.youtube.com/channel/UC-QDfvrRIDB6F0bIO4I4HkQ) channel.
