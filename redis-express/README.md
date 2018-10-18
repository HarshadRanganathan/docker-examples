# REDIS EXPRESS WEB APP

## Run Docker Compose

```
docker-compose up
```

This will build two images:

    [1] redis-server
    
    [2] node-app - connects to redis server
    
Once the docker image is built and runs, open your browser http://localhost:4001/ and refresh the page to increment the counter.

## Rebuild Image
```
docker-compose up --build
```