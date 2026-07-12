# PyQuest 🐍 — v1

Apprendre à **lire et comprendre** le Python en s'amusant, pour co-développer des apps avec Claude.

## Le fichier à déployer

**`index.html`** — c'est toute l'app dans un seul fichier. L'icône 🐍 est déjà
encodée dedans, tu n'as rien d'autre à gérer. (Le dossier `icones/` est fourni
en bonus si tu veux les images séparément, mais il n'est pas nécessaire.)

## Contenu

4 chapitres (fiches ludiques + quiz de 6 questions) : Premiers pas (print),
Variables, Conditions, Boucles. Chaque chapitre a des encarts « 🏗️ Dans une
vraie app » et des questions de lecture de code / chasse au bug.

- 10 XP par bonne réponse, +15 XP bonus sans-faute, niveaux de 🥚 à 🏆
- Il faut 4/6 à un quiz pour débloquer le chapitre suivant (rejouable)
- Progression sauvegardée automatiquement dans le navigateur

## Déployer sur GitHub Pages

1. Créer un dépôt GitHub (ou réutiliser l'existant) et y déposer `index.html`
2. Settings → Pages → Source : branche `main`, dossier `/` (root) → Save
3. Ouvrir l'URL fournie (https://tonpseudo.github.io/nom-du-depot/) sur le téléphone
4. Chrome → menu ⋮ → « Ajouter à l'écran d'accueil »

L'app apparaît avec l'icône 🐍, son nom « PyQuest », et s'ouvre en plein écran.
Pour mettre à jour : remplacer `index.html` dans le dépôt, c'est tout.

> Astuce : si tu avais déjà ajouté une ancienne version à l'écran d'accueil,
> supprime-la puis re-ajoute, sinon Chrome garde parfois l'ancienne icône.

## Code de progression

Bouton 💾 dans l'app → copier le code `PYQ1-...`.
À donner à Claude pour générer la v2 (il saura où tu en es), puis à recoller
dans la nouvelle version pour restaurer ta progression.

## La suite du curriculum

- **v2** : listes, dictionnaires et JSON (le format de données partout dans tes apps)
- **v3** : les fonctions comme briques d'un programme
- **v4** : comment une vraie app est organisée (fichiers, frontend/backend, API, base de données, Docker)
