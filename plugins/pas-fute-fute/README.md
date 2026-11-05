# Pas Fute Fute — prototype TRMNL

Affiche une expression française aléatoire depuis une API publique, sans serveur personnel.

## Source

- Dépôt : https://github.com/CorentinTh/pas-fute-fute
- API : https://pasfutefute.fr/api/quotes/random
- Champ JSON attendu : `quote`

## Installation comme plugin privé

1. Dans TRMNL, créer un **Private Plugin**.
2. Choisir la stratégie **Polling**, avec une requête **GET**.
3. Renseigner `https://pasfutefute.fr/api/quotes/random` comme URL de polling.
4. Laisser le corps et les en-têtes vides.
5. Dans l'éditeur de markup, coller [markup.html](markup.html) dans la vue **Full**.
6. Enregistrer et forcer l'actualisation ; vérifier la réponse JSON et le rendu.
7. Ajuster les espacements dans l'éditeur si nécessaire avant d'ajouter les autres formats.

Chaque actualisation interroge un endpoint aléatoire : **ce n'est pas une expression fixe par jour**.

## État

Prototype **non testé sur matériel TRMNL**. L'apparence et les variables doivent être validées dans l'éditeur. La publication comme Recipe publique n'a pas été effectuée.
