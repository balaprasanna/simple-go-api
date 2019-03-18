# Steps to build

1. Build the image
```
docker build -t balanus/newsapp:go-v1 .
```

2. Run the image
```
docker run -it -p 8000:8000 -e PORT=8000 --rm balanus/newsapp:go-v1
```

3. Push the image
```
docker login
docker push balanus/newsapp:go-v1
```
