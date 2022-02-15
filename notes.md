pulling the image
    docker pull node

creating an image
    docker build -t myapp .

see all available images
    docker images

creating a container
    docker run --name myapp_c1 myapp
    docker run --name myapp_c1 -d myapp
    docker run --name myapp_c1 -p 6000:4000 myapp

see all running containers
    docker ps

stopping a container
    docker stop myapp_c1



    