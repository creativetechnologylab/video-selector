# Instructions to install the server

1. Install [Node.js](https://nodejs.org/en/).
1. Download the server to a working director somewhere on your computer.
1. Navigate within the Terminal to that directory.
1. Type `npm install` to install the dependencies.
1. Type `npm install -g pm2`.
1. Type `pm2 start` to start the app/
1. Type `pm2 startup` and follow instructions to make pm2 run at startup.
1. Navigate to `/Users/Shared/` and create a `video` folder with the videos in it numbered `(01-20).mp4` and one called `splash.mp4`.
1. Then open your browser to: `http://localhost:3000` you could use [creativetechnologylab/web-kiosk](https://github.com/creativetechnologylab/web-kiosk) to display the interface fullscreen.
