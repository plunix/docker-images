# docker-images

Redis <br />
docker run --name redis408 -p:6379:6379 -d redis:4.0.8

Redis Commander <br />
docker run --rm --name redis-commander -d -p 8081:8081 rediscommander/redis-commander:latest

Specify single host <br />
docker run --rm --name redis-commander -d --env REDIS_HOSTS=10.10.20.30 -p 8081:8081 rediscommander/redis-commander:latest

Mongodb <br />
docker run --name mongo363 -p:27017:27017 -v /home/plunix/mongodata:/data/db -d mongo:3.6.3

adminMongo <br />
docker run -p 1234:1234 --name adminmongo -d mrvautin/adminmongo

