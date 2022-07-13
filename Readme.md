# docker container 

## 	Remove image while taking down the container
```
docker-compose down --volumes --rmi local
```

## 	Force rebuil of the image
```
docker-compose up -d --build 
```