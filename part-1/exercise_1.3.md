#### Commands:

To have a running container:
```docker run -d --name crawler ubuntu:16.04 sh -c 'while true; do date; sleep 1; done'.```

To enter the bash:
```docker exec -it looper bash```

To install curl:
```apt-get update && apt-get install curl```

To read a website:
```sh -c 'read -p "Enter website: " website; sleep 3; curl http://$website;'```

To stop the container:
```Docker kill crawler```
