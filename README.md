This is a JSON-SERVER
run the server with: npm start

https://github.com/typicode/json-server
Get a full fake REST API with zero coding in less than 30 seconds (seriously)
https://medium.com/codingthesmartway-com-blog/create-a-rest-api-with-json-server-36da8680136d
--Very similar to JSONPlaceholder (https://jsonplaceholder.typicode.com/)
But json-server has EXTREMELY STRICT ADHERENCE to RESTFUL CONVENTIONS (REST Convention: Standardized system for designing API's)

Usage:
1.create a dir, for example "apiserver"
2.inside "apiserver" dir, run the command "npm init"
3.npm install --save json-server
4.create "db.json" file, and fill the file with dummy data

5.open the "package.json" file, remove the line "test" under "scripts".
Add:
"start": "json-server -p 3001 -w db.json"
6.npm start
--NOW YOU CAN SEND RESTFUL API CALLS TO THE SERVER...(You can add, delete, update, list the records in the "db.json")
