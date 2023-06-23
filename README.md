# Getting Started with Connecting your Esri App with Rubbish Data / API

## Sample Application Setup
Software / Node Modules / Packages Being Used
- Express.js (Server package for Javascript for the backend / server side)
- React.js (Frontend package for Javascript for the frontend / client side)
- Esri / ArcGIS Geolocating / Mapping Package so that we can map data on a map and visualize the data. 

### Step 1: Setup the Server Side / Backend 
- First go into the server directory.
- run `npm install` in the terminal to install all the necessary node packages / modules
- In the server directory create a .env file to store your Rubbish Bearer Token 
- After you input the bearer token in the .env file and you've installed the node packages / modules, in the terminal run `node index.js` to start the server
- The server will then start on http://localhost:3109


### Step 2: Setup the Client Side / Frontend
- Go in to the my-app directory. 
- run `npm install` in the terminal to install all the necessary node packages / modules 
- Go to the App.js file and input your esri API Key under the esriConfig.apiKey to utilize the esri geolocating services.
- You should be able to get a free API Key if you register at https://developers.arcgis.com/
- run `npm start` in the terminal to run the app in development mode. 


