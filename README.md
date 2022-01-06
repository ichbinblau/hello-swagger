# hello-swagger
This is swagger server example for test purpose. Borrowed from https://github.com/cirocosta/hello-swagger. 

## Supported apis 
<table><tr><td>Path</td><td>Method</td><td>Summary</td></tr><tr><td>/hostname</td><td>GET</td><td></td></tr><tr><td>/ip</td><td>GET</td><td></td></tr></table>

## How to build 
- install swagger   
  `go get -u -v github.com/go-swagger/go-swagger/cmd/swagger`
- Under the project folder and run   
  `make`
- Start the Rest api server   
  `hello-swagger -p 8080`
- Request the apis
```
curl http://127.0.0.1:8080/hostname
curl http://127.0.0.1:8080/ip
```
