# Le Vieux Pisteur — maquette indépendante

Site vitrine statique pour **Le Vieux Pisteur**, snack, bar et crêperie à l’arrivée du télésiège du Jas, à Superdévoluy.

## Vérification et sources

- Activité : la carte numérique de l’établissement, crawlée en 2026, indique l’adresse à 1 920 m, une ouverture 7j/7 pendant la saison et le service de 11h30 à 15h30 ; le plan officiel 2025/26 de la station le localise toujours à l’arrivée du Jas.
- Sources : [carte officielle Menu Touch](https://app.menu-touch.fr/insite.php?id_client=15168&lang=KO), [plan des stations 2025/26](https://www.ledevoluy.com/app/uploads/ledevoluy-tourisme/2025/12/Plans-des-stations-Hiver-25-26-1.pdf).
- Logo : aucun logo réutilisable avec une autorisation explicite n’a été localisé ; le traitement nominal est provisoire et doit être remplacé par l’original approuvé.
- Photos : images d’ambiance sous licence Unsplash référencées dans le HTML ; elles ne représentent pas l’établissement. Aucune photographie sociale n’est réutilisée.

## Liens

- Dépôt : https://github.com/AMWEBDESIGNER/le-vieux-pisteur
- Pages : https://le-vieux-pisteur.pages.dev

## Parcours livré

L’accueil est complété par `experience.html` et `infos.html`, avec les services annoncés (snack, bar, crêperie), l’altitude, les conditions d’accès et l’appel direct. Confirmer météo, remontées, horaires, photos et identité avec le gestionnaire. Maquette indépendante.

## Personnalisation

Mettre à jour téléphone, logo, photos et conditions d’ouverture après validation du gestionnaire. Le site ne nécessite pas de compilation.

Maquette indépendante, sans affiliation avec l’établissement.

## Motion design et provenance du code

Animations réalisées en CSS vanilla, avec respect de `prefers-reduced-motion`, et une révélation progressive inspirée du pattern public [Scroll animation: IntersectionObserver and CSS](https://codepen.io/oscar-jite/pen/qBzwOVq). La logique reste locale, légère et adaptée à l’identité de chaque établissement ; aucune dépendance payante ni contenu généré n’est requis.

## Informations pratiques livrées

`site-enhance.js` ajoute sur l’accueil un bloc dédié à l’adresse, aux horaires, aux services, au téléphone et à l’itinéraire, ainsi qu’un footer local complet. Les informations signalées « à confirmer » doivent être validées par l’établissement avant mise en production commerciale.
