# GitMoji

Un guide emoji pour vos messages de commit !

<img src="https://raw.githubusercontent.com/ziedzaiem/gitmoji/master/screenshot.png" width="300" alt="screenshot.png" />


## Docker

- Github : https://github.com/ziedzaiemcom/GitMoji
- Docker Hub : https://hub.docker.com/r/ziedzaiemcom/gitmoji

You can use [Dive](https://github.com/wagoodman/dive) to inspect Docker image contents.

### Run

```
docker compose build
docker compose up -d
```

### Push to Docker Hub

```
docker tag gitmoji-gitmoji:latest ziedzaiemcom/gitmoji:0.0.1
docker login -u ziedzaiemcom
docker push ziedzaiemcom/gitmoji:0.0.1
```

## Crédits

Ce projet est inspiré de [gitmoji](https://gitmoji.carloscuesta.me/) par [Carlos Cuesta](https://github.com/carloscuesta/).

## Licence

MIT.
