# NestJS Base Project

### Create `.env` file
```bash
nvm use 16
cp example.env .env
nano .env

PROJECT_NAME=simple-project
PROJECT_DEFAULT_ADMIN_PASSWORD=password
PROJECT_DEFAULT_USER_PASSWORD=password

SERVER_PORT=3000
SERVER_ADDRESS=http://localhost:3000
JWT_SECRET=my_secret
JWT_EXP=86400

DB_HOST=localhost
DB_PORT=27017
DB_NAME=simple-project
DB_USER=username
DB_PASSWORD=password

REDIS_HOST=localhost
REDIS_PORT=6379
REDIS_PASSWORD=password

ONE_SIGNAL_APP_ID=abcd
ONE_SIGNAL_API_KEY=abcd
```
### Install project
```bash
npm i
npm run build
```
