# Rick and morty human database backend.

## Correr el Servidor usando:
npm install 
npm run dev 

## Github
    Fronted: https://github.com/Raulmoyano2970/RickAndMorty-Fronted 
    Backend: https://github.com/Raulmoyano2970/RickAndMorty-Backend

## Información sobre metadatos utilizados.
    {
    "name": "backend",
    "version": "1.0.0",
    "description": "Rick and morty human database backend",
    "main": "index.js",
    "scripts": {
    "start": "rimraf ./dist && tsc && node ./dist/index.js",
    "dev": "nodemon"
    },
    "author": "",
    "license": "ISC",
    "dependencies": {
    "dotenv": "^16.3.1",
    "express": "^4.18.2",
    "ts-node": "^10.9.1",
    "typescript": "^5.1.6"
    },
    "devDependencies": {
    "@types/express": "^4.17.17",
    "@types/node": "^20.5.0",
    "nodemon": "^3.0.1",
    "rimraf": "^5.0.1"
    }
    }