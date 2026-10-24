# Invitation de mariage

Site d'une seule page, pensé pour le téléphone. Aucune installation nécessaire.

## Contenu du dossier

- `index.html` : le site. **Tous les textes sont tout en haut du fichier**, dans le bloc « CONTENU À MODIFIER ».
- `photos/` : remplacez les images en gardant exactement les mêmes noms.
  - `accueil.jpg` : photo plein écran de l'accueil (idéalement verticale, 1080 × 1920)
  - `galerie-1.jpg`, `galerie-2.jpg`, `galerie-3.jpg` : les 3 photos de la galerie

Attention : les mariés avaient demandé **3 photos au total** sur le site. Il y en a maintenant 4 (l'accueil + 3 en galerie). Pour revenir à 3, supprimez une ligne dans la section `galerie` d'`index.html`.

- `carte/` : la carte d'invitation officielle (`carte-invitation.pdf`, téléchargeable depuis le site) et son aperçu (`carte-apercu.jpg`). Ces fichiers ne comptent pas dans les 3 photos.

## Modifier le site

1. Ouvrez `index.html` dans un éditeur de texte (VS Code, Bloc-notes…).
2. Changez les textes entre guillemets (prénoms, date, lieu, programme, lien du formulaire…).
3. Double-cliquez sur `index.html` pour vérifier dans votre navigateur.

Les sections « Notre histoire » et « Tenue » sont masquées pour l'instant (`afficher: false`). Passez-les à `true` quand vous avez les vrais textes et les vraies photos.

Format de la date : `AAAA-MM-JJTHH:MM:SS+01:00` (le `+01:00` correspond à l'heure du Bénin).

## Mise en ligne

Voir les étapes GitHub + Vercel données avec le projet. Après chaque modification, renvoyez les fichiers sur GitHub : Vercel met le site à jour tout seul.
"# invitation-mariage" 
