# Remote server Log Stream

## Usage:

```
docker run -v </path/to/file>:</path/to/file/in/container> -p <port>:3000 -e FILE_LOCATION=</path/to/file/in/container> akashkaveti/log-stream:latest
```

* Mount the directory where the log file is located
* Pass env variable `FILE_LOCATION`, the location of file that needs to streamed.
* Container runs on 3000 port

## Access the server

`http://<HOST_IP>:<PORT>`