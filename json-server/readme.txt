https://github.com/typicode/json-server
Get a full fake REST API with zero coding in less than 30 seconds (seriously)

Getting started:
 1) npm install -g json-server
 2) Create a db.json file with some data
    {
        "posts": [
            { "id": 1, "title": "json-server", "author": "typicode" }
        ],
        "comments": [
            { "id": 1, "body": "some comment", "postId": 1 }
        ],
        "profile": { "name": "typicode" }
    }
 3) json-server --watch db.json