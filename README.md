# GraphQL-Basic-Server
Basic server setup for express graphql

To support latest ECMA Scripts in root folder of your project run the following command:

1- npm install --save-dev babel-cli babel-preset-env babel-preset-stage-0

2- In root folder of your project add new file name it: .babelrc

3- open .babelrc and add the following code:


{
    "presets": [
        "env",
        "stage-0"
    ]
}

4- open package.json and modify your start script with the following:

  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "nodemon ./server.js --exec babel-node -e js"
  },
  
5- other details see the codes
