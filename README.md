# Le Flambeau de la Vie — Site web

Site statique moderne pour l'association **Le Flambeau de la Vie** (loi 1901), qui œuvre pour
le don d'organes et fait de l'activité physique un levier de santé pour les patients en pré et
post greffe.

Cette version est une refonte UX/UI du site original [leflambeaudelavie.fr](https://www.leflambeaudelavie.fr/),
reconstruite en HTML/CSS/JS statique (sans dépendance ni build), avec l'ensemble du contenu et des images.

## Structure

```
index.html              Accueil (mission, piliers, actions, course, partenaires)
actualites.html         À la une (congrès, recherche, évènements)
actions.html            Nos actions (vue d'ensemble)
  ├─ activite-physique.html   Promouvoir l'activité physique et sportive
  ├─ courir.html              Courir pour le don d'organes (les courses)
  └─ recherche.html           Recherches médicales (IA, activité physique, xénogreffe)
galerie.html            Galerie photos
a-propos.html           À propos de l'association
nous-soutenir.html      Faire un don / bénévolat / partenaires
contact.html            Contact
assets/
  ├─ css/style.css      Design system
  ├─ js/main.js         Navigation mobile + animations au scroll
  └─ images/            Toutes les images du site
```

## Aperçu local

Ouvrez `index.html` dans un navigateur, ou servez le dossier :

```bash
python3 -m http.server 8000
# puis http://localhost:8000
```

## Design

- Palette « flambeau » (chaleur) + vitalité/santé (teal), typographies *Plus Jakarta Sans* + *Inter*.
- 100 % responsive, navigation mobile, animations légères au défilement.
- Aucune donnée personnelle collectée ni partagée.

Contact : leflambeaudelavie@gmail.com
