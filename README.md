# Random Quotes OOP with API

[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)

Welcome to the Random Quotes app!<br>
This project consists of a client-side Vanilla JavaScript app and a server-side Express Node.js app.

## Running the App in Development Mode

### Run server

1. Navigate to the root directory of the project.
2. Open a new terminal window.
3. Change directory to the server subfolder:

   `cd server`

4. Install server dependencies by running the following command:

   `npm install`

5. Run the server in development mode with hot reload:

   `npm run dev`

6. The server will be running at http://localhost:3000

### Run client

1. Open a new terminal window in the root of the project.
2. Run the client in development mode with hot reload:

   `npx live-server client`

3. The client will be running at http://localhost:8080

## Running the App in Production Mode

### Run server

1. Navigate to the root directory of the project.
2. Open a new terminal window.
3. Change directory to the server subfolder:

   `cd server`

4. Install server dependencies by running the following command:

   `npm install`

5. Run the server in production mode:

   `npm start`

6. Configure the hosting server where you run the application to forward all requests to `http://localhost:3000`.
7. Get the URL assigned by the hosting provider for your backend API server.<br>
For example: https://random-quotes-api.com

### Run client

1. There is no need to build the client as it already contains HTML, CSS, and JS files.
2. In `client/src/config.js`, set `API_URL` to the URL assigned to the server API in step 7 of the previous section (replace http://localhost:3000).<br>
For example: https://random-quotes-api.com
3. Host all client files from the `client` subfolder on a public web server.
4. Get the URL assigned by the hosting provider for your client frontend application.<br>
For example: https://random-quotes-frontend.com
5. Open https://random-quotes-frontend.com in your web browser.
