# fake-api-server
The Rest api server to response fake randam data to test for front end application.  

## Getting Started
This project can be ran on your local environment with npm.  

### Prerequisites
You need to intall npm to work this project.  

### Installing
1. ``` npm install ```  
2. ``` npm run generate ```  

## Running the tests
1. ``` npm run server ```  

## Dependency
* [Faker.js](https://github.com/marak/Faker.js/) - Creating fake data, that library is in npm. 
* [JSON server](https://github.com/typicode/json-server) - Running server and response JSON data like Rest API, that library is in npm. 

## Usage
After running this project on your local, you can send a request to the below end-points with HTTP request method of GET/POST/PUT.  
It is possible to store your request into the DB after you request some data with POST/PUT.  

|  Request Method  |  Request URI  |  Request Content  |  Rsponse Status | 
| :--- | :--- | :--- | :--- |
|  GET  |  http://localhost:3000/users  | --  |  200  |
|  GET  |  http://localhost:3000/users/1  | --  |  200  |
|  POST |  http://localhost:3000/users/  | {name:"test"}  |  201  |
|  PUT |  http://localhost:3000/users/  | {"id":1, "name":"test"}  |  200  |

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments
The way of creating this rest api server is introduced by [the awesome article](https://hackernoon.com/back-end-data-and-api-prototyping-with-fakerjs-and-json-server-n5t36uw).  
I saw the article to create this project. Thank you for publishing very good article!  

* Hat tip to anyone whose code was used
* Inspiration
* etc
