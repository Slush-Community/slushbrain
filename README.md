# slushbrain

Run with **make run**

Build docker with **make build**

Start docker container with **make start**
```
uvicorn app.main:app --host 0.0.0.0 --port 8000

docker build -t my_fastapi_app .

docker run -d -p 8000:8000 my_fastapi_app
```


