```
git init
git clone https://github.com/atulkamble/go-helloworld
cd go-helloworld

notepad main.go
ls
go mod init
go mod init v1
go mod tidy
go build -o main
go run main.go
```
// Dockerise a go project
go --vesion
go help

cd D:/Project
mkdir goproject
cd .\goproject\

New-Item main.go
notepad main.go

// initilization
go mod init v1
go mod tidy

// build app
go build -o main

// run app
go run main.go

New-Item Dockerfile
notepad Dockerfile

// docker init
(port:8080)

// locally running container
docker compose up --build

