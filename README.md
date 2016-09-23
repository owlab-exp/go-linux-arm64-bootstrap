# GOROOT_BOOTSTRAP
This is to be used as GOROOT_BOOTSTRAP when you build golang on an arm64 linux.

## Build another version of Go on an arm64 linux system
1. git clone [https://github.com/owlab-exp/go-linux-arm64-bootstrap.git](https://github.com/owlab-exp/go-linux-arm64-bootstrap.git)
2. export GOROOT_BOOTSTRAP=<path>/go-linux-arm64-bootstrap
3. git clone [https://github.com/golang/go.git](https://github.com/golang/go.git)
4. cd go
5. git checkout <wanted version tag>
6. cd src
7. ./all.bash
