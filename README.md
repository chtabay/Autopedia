# Autopédie

Une histoire du monde écrite **de mémoire et à plusieurs mains**. Chacun répond à un questionnaire sans rien chercher : dates de vie, inventions, événements, explications de phénomènes. Les réponses se superposent en une frise. Les incohérences qui en sortent (une invention antérieure à son inventeur, deux amants qui n'ont jamais vécu en même temps) servent d'intrigues pour des exercices, des jeux et des récits d'histoire alternative.

- **Le concept, les règles de détection et les idées d'usages** : [CONCEPT.md](CONCEPT.md)
- **Le prototype** : [app/autopedie.html](app/autopedie.html)

## Le prototype

Quatre onglets :

| Onglet | Rôle |
|---|---|
| Témoigner | questionnaire de mémoire (15 personnages, 11 inventions et œuvres, 11 événements, 4 phénomènes) |
| Frise | le monde d'un témoin ou le monde commun (médianes), avec la vérité en option et un bulletin pour les exercices |
| Failles | paradoxes détectés, ressort suggéré, explications proposées par les joueurs |
| Chronique | ce que le monde croit, la trame chronologique, et une chronique écrite par Claude, à prolonger siècle après siècle |

Deux façons de l'utiliser :

- **En ligne, à plusieurs** : la page est publiée comme artifact Claude (`https://claude.ai/artifact/LtKjfCxjw8xPfNbo5AfQjj`). Les témoignages, les explications et les chroniques y sont partagés entre les personnes qui ont accès à la page. Pour qu'elles puissent témoigner, il faut la partager avec l'accès « Contributeur ».
- **Hors ligne** : ouvrir `app/autopedie.html` dans un navigateur. Les données restent dans le navigateur. On peut faire tourner l'appareil autour de la table, ou échanger les témoignages par copier-coller (onglet Témoigner, « Échanger des témoignages entre appareils »). La chronique automatique demande Claude ; hors ligne, la trame sert de base pour l'écrire à la main.

Le fichier est écrit au format des artifacts : pas de `<!doctype>` ni de `<html>`, la plateforme les ajoute à la publication. Les navigateurs l'ouvrent tel quel.
