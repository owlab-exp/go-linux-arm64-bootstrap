# GOROOT_BOOTSTRAP
This is to be used as GOROOT_BOOTSTRAP when you build golang on an arm64 linux.

## An example to build go 1.7.1
1. git clone [https://github.com/owlab-exp/go-linux-arm64-bootstrap.git](https://github.com/owlab-exp/go-linux-arm64-bootstrap.git)
2. export GOROOT_BOOTSTRAP=$(pwd)/go-linux-arm64-bootstrap
3. git clone [https://github.com/golang/go.git](https://github.com/golang/go.git)
4. cd go
5. git checkout go1.7.1
6. cd src
7. ./all.bash
