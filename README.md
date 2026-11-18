# VESTUDIO — version web personnelle

VESTUDIO est un petit site mobile en français, conçu pour Safari sur iPhone. Il ne demande ni compte, ni abonnement, ni installation d'application.

## Fonctions incluses
- Importation d'une photo depuis la photothèque.
- Réglages de luminosité, contraste et saturation.
- Aperçu avant/après.
- Détourage manuel au doigt (effacement/restauration du masque).
- Fond uni blanc, gris, beige ou charbon après détourage.
- Export JPEG.
- Bibliothèque locale IndexedDB.
- Générateur de titre, description et hashtags à partir des informations fournies.
- Recherche d'images externe via Google Images (ne vérifie pas automatiquement l'identité exacte du produit).

## Limites honnêtes
- Le détourage de cette première version est manuel, pas une IA automatique.
- Le remplacement de fond est visible autour des zones effacées manuellement.
- La recherche ouvre un moteur externe et ne certifie pas les correspondances.
- La netteté est un réglage indicatif ; la fidélité des couleurs dépend de l'écran et de la photo.
- Les données sont stockées dans le navigateur de cet iPhone. Effacer les données Safari du site peut supprimer la bibliothèque. Télécharge les images importantes dans Photos/Fichiers.
- Pour la confidentialité, les images ne sont pas téléversées par le site. Les recherches envoient les termes au moteur externe choisi.

## Hébergement gratuit : GitHub Pages
1. Crée un compte GitHub si tu n'en as pas.
2. Crée un dépôt public nommé `vestudio`.
3. Ajoute `index.html` et `sw.js` à la racine du dépôt.
4. Dans le dépôt : **Settings → Pages**.
5. Sous **Build and deployment**, choisis **Deploy from a branch**, branche `main`, dossier `/ (root)`, puis **Save**.
6. Attends la publication. Ton site sera à l'adresse `https://TON-PSEUDO.github.io/vestudio/`.

Alternative : Netlify Drop permet aussi de publier un dossier en le déposant sur https://app.netlify.com/drop (selon les conditions du service).

## Utilisation sur iPhone
1. Ouvre le lien du site dans Safari.
2. Appuie sur le bouton Partager.
3. Choisis « Sur l'écran d'accueil » si tu veux un raccourci (facultatif, aucune app à installer).
4. Pour importer : « Ajouter une photo » puis « Photothèque ».
5. Pour exporter : « Télécharger l'image ». Selon iOS, Safari peut afficher un aperçu ; utilise Partager → Enregistrer l'image ou Enregistrer dans Fichiers.

## Développement
Aucun build ni dépendance n'est nécessaire : `index.html` fonctionne directement sur un hébergement statique HTTPS.
