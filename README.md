# simple-https-file-server

## Arguments

`-d` dir to be used for a file server

`-p` port to be used, `8100` is default value

`-cert` name of certificate, `server.pem` is default value

`-key` name of certificate, `server.key` is default value

## How to use

1. make sure you have the latest version of golang installed
2. move your private key and cert to the same dir where binary will be built
3. build it `go build`
4. run `./simple-https-file-server -d .`