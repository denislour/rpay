# Rpay project

- E-commerce site with payments working with redis as `primary` database.

# Setup env

- Run docker-compose to create new redis instance

  > docker-compose up -d

- Create new .env file with the example below

  ```
  REDIS_HOST=127.0.0.1
  REDIS_PORT=6379
  REDIS_PW=redis
  ```

# How to run

- Have to run with `npm` not apply for `yarn`

  ```bash
  npm install

  npm run dev
  ```
