# Playback Synchronization and Chat App

Build project on Express, socket.io, and deployed on Heroku. App allows synchronization between users playing youtube video. 

## Accessing the Project
The project is available at: http://cool-playbacksync-chat.herokuapp.com/

## Interactive Watch party platform
![image](https://user-images.githubusercontent.com/60612625/194473545-07f975b2-0413-433e-bdd3-32136d7e4510.png)

Initialize the app by pressing the `refresh` button. Then use the `play` button as usual. Drag the timer to anywhere you want. Type in the chat box to chat with friends!

## Table of Contents:
- [How to Use](#how-to-use)
- [Deployment](#deployment)
- [Technologies Used](#technologies-used)
- [Future Direction](#future-direction)
- [Contributors](#project-maintainers)

## How to use
You must have `node.js` installed on your PC to install `JSON` packages, `express`, and `socket.io`

### Running Locally

```js
    $ git clone https://github.com/dmtrung14/playback-sync-main.git
    $ cd playback-sync-main
    $ npm install   
    $ npm install socket.io
    $ npm start
```

Your app should now be running on [localhost:3000](http://localhost:3000/).

### Deploying to Heroku

```
$ heroku create your-name-project
$ git push heroku main
$ heroku open
```
or

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Technologies Used
The keywords are related to this project:
- NodeJS
- ExpressJS
- Socket.io / Websocket
- HMTL / EJS
- CSS
- JavaScript

## Future Direction

- This project ended May 2022, but open for contributions
- Future development plans may include adding username to chatbox, paste and play custom youtube video, dividing users into rooms.

## Contributors
- Many thanks to my best friend [Duy Nguyen](https://github.com/nhdtxdy) for helping me setup and walked me through the process of implementing socketIO in this project



