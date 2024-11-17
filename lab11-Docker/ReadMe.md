
# Run following command on terminal

docker build --tag=hellodocker .

docker image ls

docker run -p 4000:80 hellodocker //4000 is the host port, 80 is the container port | -p is publish
docker run -d -p 4000:80 hellodocker

docker container stop CONTAINER_ID

docker container ls