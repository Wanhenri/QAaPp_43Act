https://auth0.com/blog/react-tutorial-building-and-securing-your-first-app/#Developing-a-Backend-API-with-Node-js-and-Express

Após seguir as etapas preliminares para a criação dos diretórios, agora seguiremos a parte do npm.

# use NPM to start the project
npm init -y

npm i body-parser cors express helmet morgan

body-parser: This is a library that you will use to convert the body of incoming requests into JSON objects.
#
cors: This is a library that you will use to configure Express to add headers stating that your API accepts 
#
requests coming from other origins. This is also known as Cross-Origin Resource Sharing (CORS).
#
express: This is Express itself.
#
helmet: This is a library that helps to secure Express apps with various HTTP headers.
#
morgan: This is a library that adds some logging capabilities to your Express app.
