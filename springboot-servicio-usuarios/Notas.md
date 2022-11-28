#docker login
docker build -t servicio-usuarios . -f .\business-b\springboot-servicio-usuarios\Dockerfile
docker build -t servicio-usuarios . -f .\Dockerfile
docker images
docker tag servicio-usuarios georgegxx/servicio-usuarios
docker push georgegxx/servicio-usuarios