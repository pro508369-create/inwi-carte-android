# Application Android — Réseau national Inwi (version connectée)

Ce projet Android Studio crée une application WebView qui ouvre la carte publiée sur :
https://inwi-zone-ftth.netlify.app/

## Avantage de cette version
La carte est chargée depuis le site hébergé. Quand le contenu du site est mis à jour et publié, l'application retrouve la version en ligne sans devoir intégrer à nouveau les données géographiques dans l'APK.

## Générer l'APK
1. Installer Android Studio et un JDK compatible (JDK 17 recommandé).
2. Ouvrir ce dossier dans Android Studio.
3. Installer/sélectionner Android SDK Platform 35 quand Android Studio le propose.
4. Laisser Gradle synchroniser le projet.
5. Choisir **Build > Build APK(s)**.
6. APK de test attendu : `app/build/outputs/apk/debug/app-debug.apk`.
7. Tester sur Android avec une connexion Internet. Pour diffusion à l'équipe, générer ensuite un APK signé depuis **Build > Generate Signed Bundle / APK**.

## Prérequis et limites
- Connexion Internet requise.
- Le site Netlify doit rester accessible.
- L'environnement utilisé pour préparer ce dossier ne dispose pas d'Android SDK/Gradle, donc l'APK n'a pas été compilé ici.
