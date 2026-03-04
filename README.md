# Comment créer son site ?

1. Tout d'abord avoir un compte Github.
2. Ensuite créer un fork de ce repository en gardant l'appelant "nom_de_votre_organisation.github.io" par exemple pour ceres-sorbonne -> ceres-sorbonne.github.io .
3. Aller dans les paramètres du repo, choisissez "Pages" dans le menu de gauche, puis dans Build and Deployments sur le champ source choississez "Github Actions" 
4. Le cloner, changer les fichiers csv et les photos dans scripts/inputs pour correspondre à votre site.
5. Dans le dossier script, lancer la commande `python init_files_from_csv.py`
6. Dans /scripts/resources changer les fichiers désirés:
  a. LogoLabo.png pour le logo qui s'affichera en haut
  b. avatar.webp pour les images par défaut des membres
  c. customisation.jsx pour changer l'introduction sur la page d'accueil ainsi que le footer
  d. icon.svg pour l'icone du site
  e. siteConfig.json pour le titre du site   
7. Add, commit et push vers github. 
8. Aller dans actions, choisir "Mettre le site en ligne", appuyer sur Run (il est possible qu'il faille cliquer sur le bouton pour activer les workflows avant)
9. Votre site devrait être en ligne sur <votre_nom_d'utilisateur>.github.io 
