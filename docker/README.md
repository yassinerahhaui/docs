# Docker

------

### 1- Dockerfile:

	- FROM -> base_image
	- WORKDIR /app
 	- COPY . .
  	- RUN 
   	- CMD ["go", "run", "."]

### 1- Commands:
	
	docker image pull <image_name>
 	docker container create <image_name>
  	docker container start <conainer_name>
   	docker container stop <container_name>
	docker run -it fedora /bin/bash
 	docker run -d centos
  	docker run -d centos sleep 20
   	docker exec -it <container_id> bash
   	docker ps -a
   	docker images -a
