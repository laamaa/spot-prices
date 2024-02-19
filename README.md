# spot-prices
With this Node.js server finnish electricity spot prices can be served to Home Assistant using REST platform to read data from local server.

## Build container

``$ podman build --pull -t bun-spotprices``

## Run container as a daemon, listening on port 8089
``$ podman run -p 8089:8089 bun-spotprices``

