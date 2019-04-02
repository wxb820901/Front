--use express generator to create project
npm install express-generator -g 
express appDemo
--install dependency required
npm install
--start locally
cd <env>/appDemo
npm start

--issue error of 'Error: Cannot find module 'jade'' 
npm instal 'jade'' 

--build docker images
docker build . -t appdemo:v1

--run docker container 
docker run -it appdemo:v1


--next step of node demo

by now I can create express node project and put some simple route ans start it on docker 
next step is rest server and client, json content parser and generate 