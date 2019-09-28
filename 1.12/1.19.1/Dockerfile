FROM circleci/golang:1.12

RUN go get -u golang.org/x/tools/cmd/goimports golang.org/x/lint/golint \
	&& curl -sfL https://raw.githubusercontent.com/golangci/golangci-lint/master/install.sh| sh -s -- -b $(go env GOPATH)/bin v1.19.1
