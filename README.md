# react-client-node-server-bootstrap

Starter kit with a nodejs server, react client(create-react-app).

A .sequelizerc file included pointed at /server. Run sequelize init at root to use.

bootstrap and react-router-dom attached to react client.

At root, npm commands:

npm client : cd client && npm run start
npm server : nodemon server.js
npm dev : concurrently --kill-others-on-fail npm run client npm run server   <=== NEEDS concurrently(install with npm install -g concurrently)

REMEMBER TO npm install at root && \client !!!