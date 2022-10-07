# Playback Synchronization and Chat App

Build project on Express, socket.io, and deployed on Heroku. App allows synchronization between users playing youtube video. 

## Accessing the Project
The project is available at: http://cool-playbacksync-chat.herokuapp.com/

## Table of Contents:
- [How to Use](#how-to-use)
- [Deployment](#deployment)
- [Technologies Used](#technologies-used)
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




