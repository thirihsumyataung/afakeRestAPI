# fakeRestAPI

### How To Get Rid of "Some error occurred Error: listen EADDRINUSE: address already in use 127.0.0.1:3000"

In terminal or VSCODE 

Step 1: `ps aux | grep node` 

Step 2; `sudo lsof -i :3000` Check PID here 

Step 3: `kill -9 1382`  ----> [ kill -9 PID ]


