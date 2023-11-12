# About
Leverages Auth0's middleware to incorporate user management routes (e.g. sign up, log in, log out) into an express.js backend

## Getting Started
```
git clone https://github.com/alexlop29/implement-express-openid-connect.git
cd implement-express-openid-connect
nvm use 20.9.0
npm install
npm run start-debug
```

## 🔧 Core Libraries
- [Node.js(20.9.0)](https://nodejs.org/en)
- [Typescript](https://www.typescriptlang.org/)
- [Express.js](https://expressjs.com/)
- [Auth0 express-openid-connect](https://github.com/auth0/express-openid-connect)
- [Dotenv](https://github.com/motdotla/dotenv)

### Development Libraries
- [Nodemon](https://nodemon.io/)


```
nvm use 20.9.0
npm init --template typescript
npm install express
npm install express-openid-connect
npm install dotenv
npm i --save-dev @types/express
npm install --save-dev --save-exact prettier
npm install --save-dev nodemon
npm install --save-dev ts-node
```

## Requirements
- Configure Auth0 Application
- Add relevant environment variables to dotenv

## References
- Include the Quick Start Guide for an Expressjs RWA
