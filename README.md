# cote-docker-network-issue

## Test on bare metal:

```bash
yarn install
node server.js
```

on another terminal panel:

```bash
node client.js

# Prints out current time
```

## Test with Docker Compose

```bash
docker-compose up
```

on another terminal panel:

```bash
node client.js

# Should print current time, but maybe not
```
