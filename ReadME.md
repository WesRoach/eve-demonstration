
## Launching Docker MongoDB
```
docker pull mongo
docker run --rm -it \
    -p 27017:27017 \
    -v $(pwd)/docker_mongo_volume/data/db:/data/db \
    mongo
```
