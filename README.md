# Carte auteur — Abderrahman EL HISSE · LN-IA

Version 1.0.0 — 20 novembre 2026.

Dépôt public : https://github.com/elhisse-CLPrepas/auteur-ln-ia

Adresse GitHub Pages : https://elhisse-clprepas.github.io/auteur-ln-ia/

GitHub Pages est activé, avec HTTPS obligatoire, sur la racine de `main`. L’état de chaque déploiement est consultable dans Actions. La carte, la photo et le logo ont été conservés ; seuls les fichiers de versionnement et cette documentation ont été ajoutés.

Ouvrir `index.html` dans un navigateur. La page fonctionne directement, sans installation et sans connexion pour les textes, la photo et le logo. Les liens externes nécessitent Internet. Le bouton « Imprimer la carte » ouvre l’impression du navigateur (avec possibilité d’enregistrement en PDF).

## Contenu

- Photo originale conservée, téléchargée depuis la page auteur.
- Logo LN-IA fourni, copié sans modification.
- Biographie et coordonnées reprises de la page auteur ; l’adresse mail utilise `elhisse@clprepas.com`, destination du bouton de contact original (le texte d’un autre lien comportait une coquille).
- Présentation enrichie et mise en page responsive, liens Facebook, LinkedIn, groupe WhatsApp et WhatsApp direct.
- Volet Web : HTML sémantique, CSS responsive, JavaScript, accessibilité, performance, référencement, prototypage assisté par IA et Git/GitHub Pages. Ces ajouts sont une proposition éditoriale de pratiques en développement, sans niveau d’expertise ni certification attribués. À adapter si nécessaire avant publication publique.

## Sources consultées le 20 novembre 2026

- Présentation : https://clprepas.com/auteur/
- Photo : https://clprepas.com/auteur/media/Prof%20EL%20HISSE.png
- Projet LN-IA et réseaux : https://elhisse-clprepas.github.io/mini-site-situation-actuelle-ia/ (liens lus dans le fichier JavaScript public chargé par cette page).
- Facebook : https://www.facebook.com/abdou.elhisse/
- LinkedIn : https://www.linkedin.com/in/abderrahman-el-hisse-556b693b5/
- Groupe « My Communité-IA » : https://chat.whatsapp.com/L900Zbek15j3tBtkJnpKaI

## Fichiers

`index.html`, `styles.css`, `script.js`, `assets/logo-LN-IA.png`, `assets/prof-el-hisse.png`.

Les fichiers sont autonomes. GitHub Pages est configuré pour publier directement la racine de la branche `main`, sans outil de construction. `.nojekyll` désactive le traitement Jekyll. Les chemins de ressources sont relatifs et fonctionnent sous le sous-dossier `/auteur-ln-ia/`.

## Versionnement local et distant

Ce dossier possède son propre dépôt Git, séparé du dossier challenge parent. Le dossier parent l’ignore pour éviter de l’enregistrer comme dépôt imbriqué. Le remote `origin` pointe vers `https://github.com/elhisse-CLPrepas/auteur-ln-ia.git` ; la branche principale est `main` et la première version porte le tag `v1.0.0`.

Depuis ce dossier, pour enregistrer et publier une modification :

```powershell
git status
git add .
git commit -m "Décrire la modification"
git push origin main
```

Chaque push sur `main` déclenche la publication GitHub Pages. Vérifiez son résultat dans [Actions](https://github.com/elhisse-CLPrepas/auteur-ln-ia/actions) et [Settings > Pages](https://github.com/elhisse-CLPrepas/auteur-ln-ia/settings/pages).

Pour créer une version ultérieure, utilisez un nouveau tag : `git tag -a v1.1.0 -m "Description de la version"`, puis `git push origin v1.1.0`.

Le dépôt et le site sont publics. La copie de cette carte intégrée à l’application `Web-developpement-ln-ia` reste indépendante : elle n’est pas actualisée par les pushes de ce dépôt.
