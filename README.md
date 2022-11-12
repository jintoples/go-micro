# Go Microservices

Go Microservices with Postgres, Mongodb, RabbitMQ, RPC, gRPC & Docker Swarm 

## Commands to remember 

Make

```bash
  make build_up
  make down
```

Docker

```bash
  cd /direktori service
  docker build -f nama-service.dockerfile -t jintoples/nama-service:x.x.x .
  docker login
  docker push jintoples/nama-service:x.x.x
```

Docker Swarm Start

```bash
  cd /project
  docker swarm init
  docker stack deploy -c swarm.yml gomicroapp
```

Docker Swarm Down

```bash
  cd /project
  docker stack rm gomicroapp
  docker swarm leave --force
```

## 📜 License

This software is licensed under the [MIT](https://github.com/nhn/tui.editor/blob/master/LICENSE) © [NHN Cloud](https://github.com/nhn).
