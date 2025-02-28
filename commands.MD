```
docker ps
```
- Displays running containers

```
docker images
```
- Displays the images are available

```
docker pulll <iamge-name>
```
- Trying to pull the images from the Docker Hub

```
docker images
```
- List all images

```
docker rmi <image_id>
```
- Remove a specific image

```
docker image prune
```
- Remove all unused images If you want to clean up all unused images (dangling images that aren't tagged and aren't used by any container)

```
docker system prune
```
- Remove all unused images, containers, and volumes

```
docker system prune -f
```
- This command will also ask for confirmation before deleting. If you want to bypass the confirmation, you can use -f:

```
docker stop <container_id>
docker rm <container_id>
docker rmi <image_id>"
```
- If the image is being used by a container (even if the container is stopped), Docker will prevent you from deleting it. If you want to force the removal, you can stop and remove the container first:




```
docker search image-name
```

```
docker info
```

```
Docker pull
```

```
docker run 
```

```
docker logs container-id
```

```
docker history image-name
```

```
docker ps -a
```

```
docker exec -it container-name /bin/sh
```

```
docker kill 
```

```
docker stop
```

```
docker network ls 
```

```
docker network inspect network-name
```

```
docker push tagged-image-name
```

```
docker rmi  
```

```
docker rm
```

```
docker rename old_container_name new_container_name
```

```
docker pause container_ID_or_name    
```

```
docker unpause container_ID_or_name  
```

```
docker port container_ID_or_name 
```

```
docker diff container_ID_or_name
```

```
docker top container_ID_or_name
```

```
docker stats
```

```
docker login & logout
```