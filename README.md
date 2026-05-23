# Nexus-core-api
const http = require("http");

const server = http.createServer((req, res) => {
  res.end("Nexus API running");
});

server.listen(process.env.PORT || 3000);
{
  "name": "nexus-core-api",
  "version": "1.0.0",
  "main": "server.js",
  "scripts": {
    "start": "node server.js"
  }
}
