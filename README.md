# Construire et déployer une application Flask à l’aide de Docker

## Créer l'image
```sh
docker image build -t flask_docker .
```

## Créer le conteneur
```sh
docker run -p 5066:5066 -d flask_docker
```

```sh
http://localhost:5066
```
