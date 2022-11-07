# EngageTech Front End Coding Challenge

Instructions to run it in development mode

## Running the back end

The back end service can be run from the `backend` directory by following these steps

1. open a terminal from the `backend` directory
2. run `npm ci` to install the dependencies required to run the back end service
3. after successful packages installation, run `npm run dev`, the starts the back end service.

If it launches correctly you should see the following in the console:

```
  > node-backend@1.0.0 dev
  > nodemon
  [nodemon] 2.0.18
  [nodemon] to restart at any time, enter `rs`
  [nodemon] watching path(s): src/**/*
  [nodemon] watching extensions: ts
  [nodemon] starting `ts-node src/server/server.ts`
  Server listening on port 6502
```

This should expose an endpoint on the following URL:
`http://localhost:6502/application/labourstats`

## Running the front end

The back end service can be run from the `frontend` directory by following these steps

1. open a terminal from the `frontend` directory
2. run `npm i` to install the dependencies required to run the front end service
3. after successful packages installation, run `ng serve`, it starts the front end service.

Finally open the following URL:
`http://localhost:4200`
