### Standalone docker compose installation
Assuming an external drive is mounted to `/mnt/data`

Copy `env.example` to `.env` with your own vars

Includes:
* Prometheus
* Grafana (pre-installed dashboards)
* Homer 7.7
* Postgres
* Heplify-Server
* Loki (not enabled in heplify-server config)
* Caddy V2 (automatic SSL based on DOMAIN env var)

Grafana is accessed via `yourdomain.com/grafana`

Run `docker-compose up -d` and :tada:
