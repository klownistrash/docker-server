# FortressOne docker compose

Set up:

```sh
docker swarm init && docker stack deploy -c docker-compose.yml fortressone
```

Tail logs:

```sh
docker container ls
docker logs -f <name>
```

Pull down:

```sh
docker stack rm fortressone && docker swarm leave --force
```

## To Do

- [x] auto update maps
- [x] auto update qwprogs
- [ ] sane default config
- [ ] integrate with discord server bot
- [ ] qtv
- [ ] autorecord and mvd file server
- [ ] stats
