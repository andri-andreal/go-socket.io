all:
	go install ./...

getdev:
	go get -t ./...

test:
	go test -race -cover -covermode=atomic ./... 

bench:
	go test -bench . -benchmem ./...
