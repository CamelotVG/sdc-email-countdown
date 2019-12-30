# countdowndocker

Build the image locally by 
```
docker build -f ./.docker/Dockerfile -t phpapp .
```

Then you can run the image as a container by
```
docker run -p 8080:80 phpapp   
```

you should then be able to open a browser to this URL
```
http://localhost:8080/gif_handler.php?campaign_id=123456&time_zone=America%7CNew_York&type=MD
```

