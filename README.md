## Simple Node Application with Dockerfile
Usage:
- `docker build` : builds an image & gives the image id (`image-id`)
- `docker run -p 3000:3000 image-id` : runs the image
- `docker ps` : checks that the image is running & gives the image name (`image-name`)
- check address `localhost:3000` with the browser
- `docker stop image-name` : stops the image's run 

One image, multiple containers.

We run containers that are based on an image : 
- the image is the template that contains the code & apps 
- containers are the running applications


