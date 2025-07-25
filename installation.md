# Système
## installation de base
suivre le lien d'installation 
https://inforeole.fr/installation-n8n-securisee-avec-traefik-postgresql-sur-docker/

motd : ```sudo nano /etc/motd```

## run le projet docker
```bash
cd /home/n8n/traefik
sudo docker compose up -d

cd /home/n8n/n8n
sudo docker compose up -d
```
lister
```bash
sudo docker container list
```

logs
```bash
sudo docker compose logs NAME_INSTANCE
```

## stop le projet docker
```bash
cd /home/n8n/traefik
sudo docker compose down

cd /home/n8n/n8n
sudo docker compose down

```
