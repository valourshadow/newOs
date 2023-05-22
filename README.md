# newOs
a simple os from MIT6.S081

# docker
jokhero/mitos

# compile
...

# command 
...

## docker in use

download image of docker: docker pull calvinhaynes412/mit6.s081:v1.3.1


run docker container : docker run -it -p[the port num] --name [the container name] -v /path to host/newOs:/home/newOs -d calvinhaynes412/mit6.s081:v1.3.1


exec docker: docker exec -it [the unicode]/[container name]
