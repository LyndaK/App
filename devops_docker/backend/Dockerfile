FROM golang:1.8


COPY src /$GOPATH/src
WORKDIR $GOPATH/src/backend


RUN go get -d -v 
RUN go install -v
RUN go build -v  main.go

EXPOSE 8080

CMD ["backend"]
