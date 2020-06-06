# docker-file
HTML for Docker

## To containerize this app, follow these steps

```yaml
docker pull engineerbaz/htmlfile:2

docker container run --name=first-docker-cont -d -p 8500:80 engineerbaz/htmlfile:2
```


That's it!!! now click on following
http://localhost:8500
