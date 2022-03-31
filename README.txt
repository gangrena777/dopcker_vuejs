
#install node js
# then open project folder( docker-vuejs)  
git clone https://github.com/gangrena777/docker_vuejs.git
cd vue-app
  npm install
#after upload files

#Dockerfile 
   docker build -t <image-name> .
   docker run -it -p 8080:8080 --rm --name <image-name>-1 <image-name>          