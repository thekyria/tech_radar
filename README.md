# thekyria's BYOR

Based on: <https://github.com/thoughtworks/build-your-own-radar>

```bash
# fetch the image - only once
docker pull wwwthoughtworks/build-your-own-radar

# start the localhost BYOR server
docker run --rm -p 8080:80 -e SERVER_NAMES="localhost 127.0.0.1" -v /${PWD}:/opt/build-your-own-radar/files wwwthoughtworks/build-your-own-radar:latest
# hit the page pointing to the self-hosted .json
start http://localhost:8080/?documentId=http%3A%2F%2Flocalhost%3A8080%2Ffiles%2Fthekyria_tech.json
```
