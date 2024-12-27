FROM golang:1.24rc1

COPY ./test /go
CMD ["./test"]

HEALTHCHECK --interval=1s --retries=90 CMD curl -f http://localhost:6060/debug/vars