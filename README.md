# MHugo Forex – obtenir l'APK
1. Créez un dépôt GitHub (privé ou public) et déposez-y tout ce dossier (y compris `.github`).
2. Onglet **Actions** > "Build APK" (se lance seul au push, ou "Run workflow").
3. Après ~5 min, téléchargez l'artefact **MHugo-Forex-apk** > installez `app-debug.apk` sur le téléphone
   (autoriser les sources inconnues).
Alternative locale : `npm i && npx cap add android && npx cap sync && npx cap open android`.
