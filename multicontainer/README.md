# MULTICONTAINER APP

![webapp](images/webapp.png?raw=true)

## Overview

![multicontainer_overview](images/multicontainer_overview.png?raw=true)

## Run Docker Compose

```
docker-compose up
```

This will build and run the following images:

    [1] postgres
    [2] redis
    [3] express api server
    [4] react web app
    [5] node js worker
    [6] nginx
    
Open your browser and visit http://localhost:4000/.

## Rebuild Image
```
docker-compose up --build
```