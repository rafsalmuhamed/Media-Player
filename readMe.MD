JSON - Deployable json file using node js

1. create a folder for json
2. inside the folder using command: npm init -y to create package.json
3. add the start command as 'node index.js' in script of package.json file
4. create .gitignore file, Add 'node_modules' inside that file
5. create index.js file
    -import json-server
    -create a server using json-server
    -create a middleware
    -setup path for db.json
    -define port
    -loisten server in  the port

6. create db.json file
7. install json server to run json file: npm i json-server.
   "npm install json-server"/npm i json-server@0.17.4
8. Add resourses to in db.json to store data   
9. To run json file using json-server: using command 'npx json-sever db.json'/node index.js