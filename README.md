# imdabigfgest.github.glitch.me
* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

html {
    font-size: 18px;
}

body {
    font-family: Helvetica, sans-serif;
}

#header {
    margin-left: 10px;
    line-height: 3.3em;
}

#chatArea
{
    position: absolute;
    top: 60px;
    width: calc(100% - 25px);
    height: calc(84%);
    margin-left: 10px;
    overflow-y: scroll;
    overflow-x: hidden;
    border: 1px solid black;
}

.chatArea__text {
    font-size: 16px;
    line-height: 1.25em;
    text-indent: 5px;
}

#inputArea {
    position:absolute;
    bottom:12px;
    width:100%;
}

#inputArea__name {
    margin-left: 10px;
    width:15%;
    height:30px;
    resize: none;
    border: 1px solid black;
    font-size: 16px;
    white-space: pre;
    overflow-wrap: normal;
    overflow-x: scroll;
    line-height: 1.7em;
    text-indent: 5px;
}

#inputArea__message {
    margin-left: 5px;
    width:74%;
    height:30px;
    resize: none;
    border: 1px solid black;
    font-size: 16px;
    white-space: pre;
    overflow-wrap: normal;
    overflow-x: scroll;
    line-height: 1.7em;
    text-indent: 5px;
}

#inputArea__sendButton {
    margin-left: 10px;
    position: absolute;
    width:8%;
    height:30px;
    border: 1px solid black;
    font-size: 12px;
}
{
  "name": "Carsons Chat room",
  "version": "1.0.0",
  "description": "A simple chat room for everyone",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "start": "node index.js",
    "dev": "nodemon index.js"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/cuinjune/chat-room.git"
  },
  "keywords": [
    "chat"
  ],
  "author": "Zack Lee",
  "license": "ISC",
  "bugs": {
    "url": "https://github.com/cuinjune/chat-room/issues"
  },
  "homepage": "https://github.com/cuinjune/chat-room#readme",
  "dependencies": {
    "body-parser": "^1.19.0",
    "express": "^4.17.1"
  }
}
* {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
}

html {
    font-size: 18px;
}

body {
    font-family: Helvetica, sans-serif;
}

#header {
    margin-left: 10px;
    line-height: 3.3em;
}

#chatArea
{
    position: absolute;
    top: 60px;
    width: calc(100% - 25px);
    height: calc(84%);
    margin-left: 10px;
    overflow-y: scroll;
    overflow-x: hidden;
    border: 1px solid black;
}

.chatArea__text {
    font-size: 16px;
    line-height: 1.25em;
    text-indent: 5px;
}

#inputArea {
    position:absolute;
    bottom:12px;
    width:100%;
}

#inputArea__name {
    margin-left: 10px;
    width:15%;
    height:30px;
    resize: none;
    border: 1px solid black;
    font-size: 16px;
    white-space: pre;
    overflow-wrap: normal;
    overflow-x: scroll;
    line-height: 1.7em;
    text-indent: 5px;
}

#inputArea__message {
    margin-left: 5px;
    width:74%;
    height:30px;
    resize: none;
    border: 1px solid black;
    font-size: 16px;
    white-space: pre;
    overflow-wrap: normal;
    overflow-x: scroll;
    line-height: 1.7em;
    text-indent: 5px;
}

#inputArea__sendButton {
    margin-left: 10px;
    position: absolute;
    width:8%;
    height:30px;
    border: 1px solid black;
    font-size: 12px;
}
