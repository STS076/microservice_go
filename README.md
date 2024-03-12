## How to Run

> ### Docker-Compose

```bash
docker-compose -f ./deployments/docker-compose/infrastructure.yaml up -d
```

> ### Build
For `building` each microservice, Run this command in root of each microservice where `go.mod` located:
```bash
go build -v ./...
```

> ### Run
For `runing` each microservice, Run this command in root of each microservice where `go.mod` located:
```bash
go run -v ./...
```

> ### Test

For `testing` each microservice, Run this command in root of each microservice where `go.mod` located:
```bash
go test -v ./...
```

