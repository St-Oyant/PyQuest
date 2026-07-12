# PyQuest 🐍 — v2.1

Apprendre à **lire et comprendre** le Python en s'amusant, pour co-développer des apps avec Claude.

## ⚠️ Important : déposer TOUS les fichiers

Contrairement à la v1, la v2 est une **vraie app installable** (comme Cortex v2.0).
Pour ça, Chrome exige plusieurs fichiers. Dépose **tout le contenu du zip à la racine
du dépôt GitHub** :

- `index.html` — l'app
- `manifest.json` — la carte d'identité de l'app (nom, icône, plein écran)
- `sw.js` — le « service worker », qui rend l'app installable et utilisable hors ligne
- `icon-192.png` et `icon-512.png` — les icônes

## Installer sur le téléphone

1. Dépose les 5 fichiers dans le dépôt GitHub (remplace les anciens)
2. Settings → Pages → branche `main`, dossier `/` (root) si pas déjà fait
3. Ouvre l'URL sur le téléphone dans Chrome
4. Chrome devrait proposer **« Installer l'application »** (menu ⋮ ou bandeau) —
   c'est bien « Installer », pas juste « Ajouter à l'écran d'accueil »

> Si tu avais l'ancienne version en raccourci : supprime-la de l'écran d'accueil,
> recharge la page (une ou deux fois, le temps que le service worker s'active),
> puis installe. Chrome peut mettre ~1 min à proposer l'installation.

## Nouveautés v2 et v2.1

- **Structure** : Chapitre 1 « Les bases » (4 leçons) + Chapitre 2 « Les données »
  (listes, dictionnaires, JSON — les structures des vraies apps)
- **Swipe** gauche/droite pour naviguer entre les fiches
- **Geste retour** Android : sort de la leçon et revient à l'accueil (au lieu de quitter)
- Réponses des quiz : affichage uniforme (fini les mélanges de polices)
- Questions retravaillées : de nouveaux exemples qui obligent à appliquer le concept
  (plus de réponse par mémoire visuelle des fiches 😉)
- Niveaux rééquilibrés : 6 niveaux jusqu'à « Légende du Python 🐉 » (~sans-faute partout)
- Fonctionne hors ligne une fois installée
- **v2.1** : accueil par chapitres (fini la liste infinie !) avec notes agrégées par chapitre
  (étoiles, leçons réussies, bonnes réponses) ; on entre dans un chapitre pour voir ses leçons ;
  le geste retour remonte niveau par niveau (leçon → chapitre → accueil)

## Code de progression

Bouton 💾 → copier le code `PYQ2-...`. Les anciens codes `PYQ1-...` sont acceptés.
À donner à Claude pour la v3, puis à recoller dans la nouvelle version.

## Prochaines étapes du curriculum

- **v3** : les fonctions comme briques d'un programme + lire un vrai petit programme complet
- **v4** : comment une vraie app est organisée (fichiers, frontend/backend, API, base de données, Docker)
