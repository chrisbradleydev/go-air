# go-air

Clone the repository.

```sh
git clone https://github.com/chrisbradleydev/go-air.git .
```

Build Docker image.

```sh
docker build -t go-air .
```

Run Docker container.

```sh
docker run -p 8080:8080 -v $(pwd):/app -v /app/tmp go-air
```
