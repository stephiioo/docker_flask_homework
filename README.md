# docker_flask_homework

## The objective for this homework was to provide hands-on experience in Dockerizing Flask applications, first individually and then using Docker Compose for managing multiple applications.

## part 1:

### Create a flask app and add a requirements.txt file then create your docker file

### to build image: docker build -t <image_name> 

### to run image: docker run-p 5000:5000 <image_name>

### to delete image: docker run -d -p 5000:5000 <image_name>

### to check if the image is running: docker ps

### to stop image: docker stop <container_id>

### to delete image: docker system prune -f -a


## Part 2:

### create a docker-compose.yml file

### to build containers: docker-compose up --build

### to stop containers: docker-compose down

### to remove containers: docker-compose rm



### docker-compose vs. docker:

#### A major difference between docker versus docker-compose is that docker is entirely command line based, while docker-compose reads configuration data from a YAML file

#### Another major difference is that docker run can only start one container at a time, while docker-compose will configure and run multiple

### challenges: there were no major challenges encountered while completing this assignment
