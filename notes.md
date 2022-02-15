pulling the image
    docker pull node

creating an image
    docker build -t myapp .
    docker build -t myapp:v1 .

see all available images
    docker images

delete an image
    docker image rm myapp
    docker image rm myapp -f

creating a container
    docker run --name myapp_c1 myapp
    docker run --name myapp_c1 -d myapp
    docker run --name myapp_c1 -p 6000:4000 myapp
    docker run --name myapp_c1 -p 6000:4000 myapp:v1

see all running containers
    docker ps
    docker ps -a

stopping a container
    docker stop myapp_c1

deleting a container
    docker contaier rm myapp_c1

delete all images, containers and volums
    docker system prune -a



    