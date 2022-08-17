# Monitoring

Changes:

docker-compose:
- replace "external-network"

prometheus.yml:
- replace "remote-write"
- replace "container-name"
- replace "container-port"

promtail.yml
- replace promtail-url
- replace docker-target

# start up

docker-compose up -d
