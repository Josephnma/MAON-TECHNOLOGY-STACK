
# Maon-backend

This backend challenge is a clone that mimics stackoverflow.

The clone covers only 4 basic endpoints to enable users ask questions. It focuses on only the question , comment , search , and single question retrieval service.

## Technlogy Stack

Maon Backend Challenge is built using Nodejs , Express , MongoDB , Redis , and the ELK Stack

-   
## Configuration

Configure the project before you launch it by doing the following :

-   Create a .env file in the root of the application
    The content of the file should contain the following :

>

    LocalDB = "mongodb://127.0.0.1:27017"

    dbName = "maon"

    Server_Port = 4000

Ensure you install Redis , and ElasticSearch on your device

### Getting Started

-   Run this command to launch the development server : npm run devstart
-   Add a Question
-   Search for a question
-   Retrieve a question
-   Add comments to a question

