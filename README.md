# HandsOnTypeScript-Server
This will be the backend for the hands on typescript book learning material

# Redis commands

https://redis.io/docs/install/install-redis/install-redis-on-windows/

sudo service redis-server start

redis-cli

sudo service redis-server stop

## NPM commands

npm init -y

npm i express express-session connect-redis ioredis dotenv

express: for express

express sessions: enables sessions in express

connect-redis: connects our express session to redis data store

ioredis: access to redis server itself

dotenv: will allow us to use config file .env 

npm i typescript @types/express @types/express-session @types/connect-redis @types/ioredis ts-node-dev -D