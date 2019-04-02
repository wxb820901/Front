--use express generator to create project
npm install express-generator -g 
express appDemo

--start locally
cd <env>/appDemo
npm start

--issue error of 'Error: Cannot find module 'jade'' 
npm instal 'jade'' 

--build docker images
docker build . -t appdemo:v1

--run docker container 
docker run -it appdemo:v1