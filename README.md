# pgadmin4-electron-app
Intégration de Pgadmin4 avec Electron.

## Installation
- Cloner le dépôt : `git clone https://github.com/jpm-cbna/pgadmin4-electron-app.git`
- Se placer dans le dossier : `cd pgadmin4-electron-app`
- Installer NVM (si nécessaire) : `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.0/install.sh | bash`
- Installer NPM (utilise la version définir dans `.nvmrc`) : `nvm install`
- Charger la version de NPM nécessaire au projet : `nvm use`
- Installer les dépendances : `npm install`

## Utilisation
- Vous devez avoir PgAdmin4 fonctionnant sur l'url : http://127.0.0.1:5050/
- En se placant dans le dossier *pgadmin4-electron-app*, lancer : `npm start`

## Problèmes

### Page blanche
- Vérifier que PgAdmin4 fonctionne en tant que service.
- Vérifier avec votre navigateur ce qui s'affiche sur l'URL : http://127.0.0.1:5050/

