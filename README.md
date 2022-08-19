docker compose up -d

"scripts": { <br />
"main": "tsc && node ./dist/main.js", <br />
"test": "tsc && jest ./dist", <br />
"express": "tsc && node ./dist/src/infra/http/express.js", <br />
"hapi": "tsc && node ./dist/src/infra/http/hapi.js" <br />
},