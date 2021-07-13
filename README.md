# teams-clone-engage
This is a P2P Teams clone 

## Heroku link
This app is hosted on heroku as it is **best viewed** there
https://teams-clone-kavyasri.herokuapp.com

## Features
- Video Call

### Running this web app 
- open the project containing folder in a terminal. 
- type '**npm i**' to install the dependencies
- after successfully installing dependencies, type '**npm start**'
- your server is on and you can now add clients or Peers.

### Join the client (Peer-1)
- goto **http://localhost:3030**
- The web page redirects you to a room. the room-id can be seen after the localhost address. 

### Join another client (Peer-2)
- paste the link after getting redicted in the previous step. (_If you visit http://localhost:3030/ directly, you will be redirected to another room so that you cannot see your friend in there._)

### Join still more peers...
- keep on pasting the link in new browser tab. 
**Note:** You will see a lag as number of clients increase.

### Scalability
- Since this is a P2P call, it is not scalable.
- This project was built on peerjs and express
- Suitable for 1 to 1 calls and small scale group calls

