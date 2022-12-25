# camera.ui unofficial docker image
## Run with docker-compose
```
version: '3.7'

services:
  camera.ui:
    container_name: camera.ui
    image: nexryai/camera.ui:latest
    ports:
     - "8081:8081"
    volumes:
      - ./data:/.camera.ui:rw
```

