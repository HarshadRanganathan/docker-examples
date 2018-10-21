# REDIS EXPRESS WEB APP

## Run Docker Compose

```
docker-compose up
```

This will build and run two images:

    [1] redis-server
    
    [2] node-app - connects to redis server
    
Open your browser and visit http://localhost:4001/. Refresh the page to increment the counter.

## Rebuild Image
```
docker-compose up --build
```