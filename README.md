# pocnonmarchand.org

POC d'outils numériques pour le secteur non marchand.

## Structure

```
/                    → Page d'accueil (landing page)
/gestreunion/        → GestRéunion - Gestion des réunions d'équipe
```

## Déploiement

Le déploiement est automatisé via GitHub Actions. Chaque push sur `main` déclenche un déploiement FTP vers Hostinger.

### Secrets requis (Settings > Secrets and variables > Actions)

| Secret | Description |
|--------|-------------|
| `FTP_HOST` | Adresse du serveur FTP Hostinger |
| `FTP_USERNAME` | Nom d'utilisateur FTP |
| `FTP_PASSWORD` | Mot de passe FTP |
