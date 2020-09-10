npm install -g json-server

create a json object in file db.json
{
  "people": [
    {
      "id": 0,
      "name": "george"
    }
}

now run it with json-server db.json

it will expose as localhost:3000 fake server with GET POST PUT ...
localhost:3000/people POST Request Body {"name":"Vinayaka"}, and type text : JSON
localhost:3000/people GET 
localhost:3000/people/1 PUT Request Body {"name":"VinayakaBR"} , and type text : JSON
localhost:3000/people/0 GET localhost:3000/people?q=shawn

STEP 2 

npm install faker lodash

create class generate.js file

json-server generate.js // Lot of fake of objects




