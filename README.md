# Souplothèque – tapis roulant 3D

Fichiers de la scène d'accueil du site.

- `tapis3d.js` : le script (ne pas modifier à la main)
- `logo/souplotheque.svg` : le logo, transformé en lettres 3D souples
- `modeles/` : objets 3D (.glb, idéalement moins de 1 Mo, posés au sol)
- `objets/` : objets en images détourées (.webp ou .png transparents)

## Ajouter ou remplacer un objet
1. Déposer le fichier dans `modeles/` ou `objets/` (bouton **Add file > Upload files**).
2. Dans Webflow, ajouter l'objet dans la collection « Objets du tapis » avec son adresse :
   `https://cdn.jsdelivr.net/gh/NOM_UTILISATEUR/souplotheque-tapis@main/objets/nom-du-fichier.webp`
3. Régler sa taille (0,4 = petit, 1 = moyen, 1,6 = grand) et, pour un .glb, sa couleur.

Remplacer un fichier en gardant le même nom : la mise à jour peut mettre jusqu'à quelques heures à apparaître.
