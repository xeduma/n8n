# n8n installation

# Sommaire
 - [commandes système](#système)

projets : 
 - [Minecraft](Minecraft.md)
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
### lister les docker en route
```bash
sudo docker container list
```

## stop le projet docker
```bash
cd /home/n8n/traefik
sudo docker compose down

cd /home/n8n/n8n
sudo docker compose down

```
