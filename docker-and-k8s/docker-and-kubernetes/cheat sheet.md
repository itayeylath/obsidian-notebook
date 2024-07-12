create image 
docker run -d -p 3000:80  --rm --name feedback--app -v feedback:/app/feedback feedback-node:volumes

create containers with editable and persistent data data
 docker run -d -p 3000:80 --name feedback--app -v feedback:/app/feedback -v "/home/developer/Development/projects/data-volumes-03-adj-node-code/data-volumes-03-adj-node-code:/app" -v /app/node_modules  feedback-node:volumes


