# ERN Stack Boilerplate
This is a basic boilerplate to build full-stack React/NodeJS web applications. It uses:

* [Create-React-App](https://create-react-app.dev/) to build client 
* [Express](https://expressjs.com/) to build server and backend APIs, connected to client via proxy
* [Axios](https://github.com/axios/axios) for consuming APIs 
* [Nodemon](https://nodemon.io/) to automatically rerun server when file changes are detected
* [Concurrently](https://github.com/kimmobrunfeldt/concurrently#readme) to run the client and server at the same time in development
 
With this boilerplate, you're free to choose the database layer you want to incorporate into your project. Additionally, though Create-React-App ships with CSS, you can easily switch to your preferred method for styling components.

## Folder Structure
At the root of the project, there are two directories: client and server. React/frontend code can be found in the client directory and backend code is found in the server directory. 

## Setup/Usage
1. Clone the repository and & change folder name if necessary using `git clone https://github.com/rchlblns/ern-boilerplate.git <your-app-name>`

2. Move into the repo: `cd <your-app-name>`

3. Run `npm install` to install dependencies

4. Run `npm run dev` to start the development server

5. Open [http://localhost:3000](http://localhost:3000) to view the app in your broswer and get started!

To create a production build, run `npm run build:client` and `npm start`. Client code is bundled into static files and served by the Node.js/Express application.

## Requirements
[Node](https://nodejs.org/en/) 14.5+

## License
[MIT](./license.md)


