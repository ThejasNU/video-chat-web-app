# Video Chat Web App

It has been built using React, Material UI, Socket.io and WebRTC.

To open this on your browser [click here](https://webrtc-videochat-web-app.netlify.app/)

Backend has been deployed on heroku and frontend has been deployed on netlify

### To run this locally on your device

1. Clone this repo 
2. Open terminal in the root directory of this project and run `yarn install`
3. Execute the command `node index.js` 
4. Execute `cd ./client`
5. Now in client directory, run command `yarn install`
6. Go to src/SocketContext.js and put `http://localhost:7777` in the socket initialisation function
7. Now execute `yarn start` and open `http://localhost:3000` in your browser
