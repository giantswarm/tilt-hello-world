FROM alpine
WORKDIR /app
ADD web web
ADD build/tilt-example-go tilt-example-go
ENTRYPOINT /app/tilt-example-go
