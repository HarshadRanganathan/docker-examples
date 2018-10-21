# REACT WEB APP

## Install Dependencies

```
npm install
```

## Run Docker Compose (Dev)

```
docker-compose up
```

This will build and run `react-app` dev image.
    
Open your browser and visit http://localhost:3000/ to view the app.

Note:
The container references the files in your local machine. Any changes you make to the local files should also get reflected in the container without requiring to re-build the images.


## Rebuild Image
```
docker-compose up --build
```

## Run Tests

```
docker exec -it <container_id> npm run test
```

## Serve Production Build via Nginx

Generate static assets and create image

```
docker build .
```

Run the nginx container

```
docker run -p 8080:80 <container_id>
```