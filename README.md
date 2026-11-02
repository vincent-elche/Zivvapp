# Zivv App

Application Android personnalisée pour l'instance HumHub **zivv.eu**.

Basée sur le projet officiel [humhub/app](https://github.com/humhub/app) en mode **Flavored Build**.

## Configuration

Le fichier `assets/.env` contient les paramètres de l'instance :

```
MANIFEST_URL=https://zivv.eu/manifest.json
DISPLAY=standalone
START_URL=https://zivv.eu
SHORT_NAME=Zivv
NAME=Zivv App
BACKGROUND_COLOR=#ffffff
THEME_COLOR=#1976d2
```

## Build

1. Cloner le repo officiel : `git clone https://github.com/humhub/app`
2. Copier ce fichier `assets/.env` dans le projet
3. Compiler avec Flutter

## Notifications

Pour les push notifications, configurer le module `fcm-push` côté serveur avec un projet Firebase personnel.
