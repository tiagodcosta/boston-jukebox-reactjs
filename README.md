# Boston Touch Jukebox

Project that lets people listen to music based on their mood (brain sensor reading)

Made with ReactJS, Arduino, NodeJS

## Motivation

The Boston Touch Jukebox uses the concept of "media as a software" (Lev Manovich, 2012) to expand the sensorial scope of music. It aims to provide a complete and new experience to music listeners. They will not only listen to music but also feel and touch music.

The project merges IoT and Web Development to expand the sensorial scope. Headband sensors are used to capture the user's mood, and touch sensors attached to objects give users the opportunity to choose music based on touch. Firebase is used to store information about songs.

![Alt text](https://preview.ibb.co/nQQk8k/screen.png " ")
## Getting Started

**Important:** You need a brain sensor headband [Neurosky](http://neurosky.com/) and an Arduino connect to an [Adafruit 12 X Capactive Touch Shield MPR121](https://www.adafruit.com/product/2024)

First

`npm install` or  `yarn install`

Second

 `node server`

 and then

`yarn start` or `npm start`

Open the browser `localhost:9090`

**Important** - The brain sensor can take almost 30s to start to send data.

## Author

Tiago Costa

## License

This project is licensed under the MIT License