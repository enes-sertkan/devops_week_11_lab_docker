# Run following command on terminal

docker build --tag=101403883_hello_docker .

# another way

docker build -t 101403883_hello_docker .

docker image ls

docker run -d --name=lab11DevOps -p 4000:80 101403883_hello_docker

docker container stop CONTAINER_ID

docker container ls
