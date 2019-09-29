FROM circleci/golang:1.13

RUN GO111MODULE=on go get -u golang.org/x/tools/cmd/goimports@e7abfed golang.org/x/lint/golint@414d861 \
	&& curl -sfL https://raw.githubusercontent.com/golangci/golangci-lint/master/install.sh| sh -s -- -b $(go env GOPATH)/bin v1.19.1
