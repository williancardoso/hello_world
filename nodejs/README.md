# NodeJS

Building image
```
git clone https://github.com/williancardoso/hello_world.git
cd hello_world/nodejs
docker build -t <tag> .
```

running
```
docker run -d -p 80:80 --name=nodejs <tag>
```
