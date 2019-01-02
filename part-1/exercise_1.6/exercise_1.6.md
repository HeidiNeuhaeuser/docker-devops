#### Commands:
```docker build -t ex6 .```

```docker run -it -p 2222:8000 -v $(pwd)/backend-example-docker/logs.txt:/mydir/logs.txt ex6```