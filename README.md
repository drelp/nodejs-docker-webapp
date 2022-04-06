# nodejs-docker-webapp

```shell
docker build . -t yiluxiangbei/node-web-app
docker images
docker run -p 49160:8080 -d yiluxiangbei/node-web-app
docker ps
docker logs <container id>
docker exec -it <container id> /bin/bash
```
