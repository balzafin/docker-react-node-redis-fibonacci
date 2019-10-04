Input (index) will be sent from the client to the worker (via node server) which calculates the fibonacci number.<br>
The worker saves the calculations to the redis db.<br>
The nginx will redirect api request to the the node server and root request to the React server.<br>
<br>
The clien is accesible from **localhost:3050**

## Build an start up

```
docker-compose up
```

## Rebuild

```
docker-compose up --build
```

## Terminate

```
docker-compose down
```
