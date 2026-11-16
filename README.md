# Ma Dictée Magique

Application éducative de dictée pour les enfants de 4 à 8 ans.

## Déploiement
Site statique, sans serveur ni base de données. Copier les fichiers à la racine HTTPS de `dictee.nopuna.fr` sur o2switch.

## Fonctionnement
- Deux niveaux : lettres à remettre dans l'ordre et dictée libre
- Synthèse vocale française via le navigateur
- Progression locale, sans compte ni collecte de données
- PWA avec service worker et mode hors connexion après première visite

## Développement
Ouvrir `index.html` sur un serveur HTTP local (par exemple `python3 -m http.server 8000`), puis consulter http://localhost:8000.

## Limites
La disponibilité de la voix hors ligne dépend du navigateur et des voix installées sur l'appareil.
