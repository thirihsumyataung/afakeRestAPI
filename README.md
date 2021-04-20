# fakeRestAPI

### How To Get Rid of "Some error occurred Error: listen EADDRINUSE: address already in use 127.0.0.1:3000"

In terminal or VSCODE 

Step 1: `ps aux | grep node` 

Step 2; `sudo lsof -i :3000` Check PID here 

Step 3: `kill -9 1382`  ----> [ kill -9 PID ]


### How to start a FAKE API JSON File 

Step 1: `npm install -g json-server`

Step 2: `npm init`

STep 3: `Create a Json File` 

Step 4: `npm install --save json-server` 

Step 5: `"script" : { "json:server": "json-server --watch database.json"}` Your Json File name here 

Step 6: `npm run json:server`

Step 7: `localhost:3000`

### CRUD : PostMan  

`GET: http://localhost:3000/users` ---> You can access the data in your json file 

`Patch: http://localhost:3000/users/3`----> 3 stands for the id of the data you want to update , and you can update their information. 

`Post :http://localhost:3000/users` ----> You can add more data in your jSON file 

<span style="background-color: #FFFF00">Marked text</span>


