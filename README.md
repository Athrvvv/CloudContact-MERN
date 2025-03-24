# Cloud Contact

Cloud Contact App allows users to register, log in, and manage their contacts securely in the cloud. The project uses Node.js, Express, and MongoDB for the backend and React with Redux for the frontend.

## Installation Instructions

### Prerequisite: Set Node Version to 16.x Using NVM
1. Install NVM:
```bash
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
```
2. Restart terminal and install Node 16:
```bash
nvm install 16
```
3. Set Node version:
```bash
nvm use 16
```

## Install Dependencies for Server
```bash
npm install
```

## Install Dependencies for Client
```bash
npm run client-install
```

## Run Client & Server Concurrently
```bash
npm run dev
```

## Run Express Server Only
```bash
npm run server
```

## Run React Client Only
```bash
npm run client
```

### Server: [http://localhost:5000](http://localhost:5000)  
### Client: [http://localhost:3000](http://localhost:3000)

---

👉 Make sure to add your MongoDB URI and JWT secret to `config/default.json` before running.

========Thank You !!!=========

