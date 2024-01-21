# thekyria's BYOR

Based on: <https://github.com/thoughtworks/build-your-own-radar>

```bash
docker pull wwwthoughtworks/build-your-own-radar
docker run --rm -p 8080:80 -e SERVER_NAMES="localhost 127.0.0.1" -v /${PWD}:/opt/build-your-own-radar/files wwwthoughtworks/build-your-own-radar:latest
start http://localhost:8080/?documentId=http%3A%2F%2Flocalhost%3A8080%2Ffiles%2Fsample_tech.json
```
