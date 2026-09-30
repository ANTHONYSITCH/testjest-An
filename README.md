# Todo list React

Application frontend React avec Vite et Jest : ajouter, terminer, réactiver et supprimer des tâches. Les tâches restent en mémoire et sont réinitialisées au rechargement.

## Démarrer

Node.js 22.12+ et npm.

```sh
npm ci
npm run dev
```

## Vérifier

```sh
npm test
npm run build
```

Jest impose une couverture minimale de 50 % pour les lignes, branches, fonctions et instructions. Le point d'entrée React est exclu de la couverture. Le rapport HTML est disponible dans `coverage/lcov-report/index.html`.

`npm run test:watch` lance les tests en mode interactif et `npm run preview` sert le build de production.
