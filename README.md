# ng-tetris

Tetris game in Angular. [Play it now!](https://focused-mestorf-930f82.netlify.com/)

Read the [blog about making the game](https://medium.com/angular-in-depth/game-development-tetris-in-angular-64ef96ce56f7?sk=66ab4b5774919de28eecd3a2662557a4) 

![tetris picture](src/assets/share-image-large.png)

## Development server

Run `npm start` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.


## Installation 

1. Clone the repo
   ```sh
   git clone git@github.com:Datacog1/ng-tetris.git
   ```
2. Install NPM packages
   ```sh
   npm install
   ```
3. Run the command
   ```sh
   ng serve
   ```
## Building the image and container

1. Build the image
	nerdctl build -t tetris:v1 .
2. Running the image on port
	nerdctl -p 8080:80 tetris:v1 
3. Running the image in shell 
	nerdctl run -it tetris:v1 sh

##For Dowloading my image
https://hub.docker.com/repository/docker/amnarahman/ng-tetris