--build docker images
docker build . -t appdemo:v1

--run docker container 
docker run -it appdemo:v1