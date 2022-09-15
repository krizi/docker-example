

# command
docker run -it --rm -d -p 8080:80 --name web -v ~/site-content:/usr/share/nginx/html nginx

docker exec -ti <container-name> bash 

# see
https://www.docker.com/blog/how-to-use-the-official-nginx-docker-image/