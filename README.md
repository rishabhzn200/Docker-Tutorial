<h1>Docker-Tutorial</h1>
<br/>

Download the Files<br/>
Create a Dockerfile<br/><br/>

Build the Dockerfile<br/>
docker -p 80:80 \<<b>name</b>\><br/><br/>

Run<br/>
docker run -p 127.0.0.1:80:80 \<<b>name</b>\><br/><br/>

Get the NAME of container<br/>
docker ps

Attach to Docker container login shell<br/>
docker exec -it \<<b>container_name</b>\> bash
