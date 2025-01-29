# Commande de création d'un server de base de données


### Se connecter

`ssh root@...`

### Faire les mises à jour et les améliorations
```bash
apt update`

`apt upgrade`
```

### Installer le server maria-db
```bash
apt install -y mariadb-server
```
Pour voir le port ouvert (3306)
```bash
ss -tulpn
```