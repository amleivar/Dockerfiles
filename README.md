# Dockerfiles

Create the image
```
docker build -t qt59dev .
```

Launch it on Windows using Xming. Change IP_ADDRESS to whatever address your host might have
```
docker run -it --name devqt59 -e DISPLAY=IP_ADDRESS:0.0 dev-qt59
```
