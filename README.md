# json-server
Create a json-server in next js app sample

step 1)
install json-server using "npm install json-server"

step 2)
add a .json file in root project and add fake data

step 3)
in package.json file in scripts property add new property for example: "json-server": "json-server --watch db.json"
db.json => file name
if you want run in specific port add --port: "json-server": "json-server --watch db.json --port your port number"

step 4)
in termminal: npm run json-server
json-server => name of property that defined
