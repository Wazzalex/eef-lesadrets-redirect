# eef-lesadrets-redirect

Ce dépôt ne contient qu'une page de redirection : il est publié par GitHub Pages sur
**eef-lesadrets.fr** (second nom de domaine de l'association École en Fête) et envoie
chaque visiteur vers le site principal, **https://ecoleenfete-lesadrets.fr**
(code du site : [Wazzalex/eef-website](https://github.com/Wazzalex/eef-website)).

- `index.html` et `404.html` : la même page de redirection (404.html couvre toutes les
  autres adresses, ex. eef-lesadrets.fr/potee) ; l'ancre éventuelle est conservée
  (eef-lesadrets.fr/#agenda → ecoleenfete-lesadrets.fr/#agenda).
- `CNAME` : le domaine servi par ce dépôt.
- `.nojekyll` : publie les fichiers tels quels.

Réglages : Settings → Pages → *Deploy from a branch* (`main`, `/ (root)`), *Custom domain*
`eef-lesadrets.fr`, *Enforce HTTPS* coché. Zone DNS OVH de eef-lesadrets.fr : mêmes
enregistrements A / AAAA / CNAME www que le domaine principal (voir le README d'eef-website).
