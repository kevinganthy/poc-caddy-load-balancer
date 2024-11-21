# POC caddy load balancer

## Utilisation

Trois services sont définis :

* Caddy
* Front 1
* Front 2

```bash
docker-compose up -d
```

Se connecter sur <http://localhost> pour voir le load balancer en action.

Configuration actuelle en round-robin.
