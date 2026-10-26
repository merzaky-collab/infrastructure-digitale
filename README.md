# Réseaux informatiques · Infrastructure digitale

Application web pour les stagiaires OFPPT de 1re année (Infrastructure digitale) :
7 thèmes, 29 leçons, chacune avec une fiche de cours, une simulation et un QCM corrigé.

Site en ligne : https://infrastructure-digitale.netlify.app/

## Organisation
Le thème « La redondance des réseaux » (leçons 27 à 29) couvre les atouts de la redondance, STP et VRRP, avec les simulations `simRedund`, `simStp` et `simVrrp`.

Tout le site tient dans `index.html` (HTML, CSS et JavaScript, sans dépendance à installer).
- Les leçons sont dans le tableau `THEMES`, les thèmes dans `CHAPS` et `CLEAD`.
- Chaque simulation est une fonction déclarée dans `SIMS`.
- Le thème « Les VLAN » ajoute `simVlanBc` (diffusion), `simLab` (lab interactif) et l'onglet Lab (`labTabHTML`).

## Publication
Le dépôt est relié à Netlify : chaque modification poussée sur la branche `main`
est publiée automatiquement (fichier `netlify.toml`, aucune étape de build).
