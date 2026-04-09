# Contribuer à ce projet (projet de test)

Merci de votre intérêt pour ce petit projet de test. Ce dépôt contient une page HTML/CSS simple. Même si l'ampleur est réduite, nous appliquons un processus clair pour garder l'historique propre et les contributions faciles à intégrer.

## Code de conduite
Ce projet adhère au Code de Conduite inclus dans `CODE_OF_CONDUCT.md`. En participant, vous vous engagez à le respecter.

## Comment signaler un bug
Avant d'ouvrir un ticket :
- Vérifiez qu'un ticket similaire n'existe pas déjà (onglet Issues de GitHub).
- Assurez-vous d'utiliser la dernière version disponible de la branche principale.

Si vous ne trouvez rien de pertinent, ouvrez une nouvelle Issue avec :
- Un titre clair et concis.
- Une description du problème incluant :
  - Étapes précises pour reproduire
  - Comportement attendu
  - Comportement observé
  - Environnement (navigateur et version, système d'exploitation)
  - Si possible, une démonstration minimale (ex. CodePen, JSFiddle, ou un petit extrait de code) montrant le problème sur une copie d'`index.html` / `style.css`.

Sécurité : si vous pensez avoir découvert une vulnérabilité, merci de ne pas créer d'Issue publique. Utilisez, si disponible, l'outil "Security advisories" de GitHub ou contactez le mainteneur en privé (via le profil GitHub).

## Proposer une correction (bugfix)
1. Forkez le dépôt et créez une branche dédiée : `fix/description-courte-du-bug`.
2. Faites des commits petits et explicites.
3. Vérifiez localement en ouvrant `index.html` dans votre navigateur (un simple serveur HTTP est facultatif : `python3 -m http.server` par exemple).
4. Ouvrez une Pull Request (PR) vers `main` avec :
   - Une description claire du problème et de la solution
   - Une référence à l'Issue correspondante (ex. "Fixes #123")
   - Des captures d'écran si le rendu visuel change

## Changements purement cosmétiques
Les PRs qui ne font que reformater/retoucher du style sans bénéfice clair (lisibilité, accessibilité, cohérence, correction) peuvent être refusées. Si vous proposez un ajustement visuel, expliquez l'objectif (par exemple : meilleur contraste, conformité a11y, cohérence du design).

## Nouvelles fonctionnalités ou changements de comportement
- Commencez par ouvrir une discussion (Issue de type "feature request") pour valider l'intérêt et le périmètre.
- Une fois un consensus trouvé, implémentez sur une branche `feat/description-courte`.
- Documentez le changement dans `README.md` si nécessaire et, si le visuel évolue, ajoutez des captures d'écran.

## Questions
Pour des questions générales :
- Utilisez idéalement l'onglet Discussions (si activé) ; sinon, ouvrez une Issue avec l'étiquette "question".

## Style, format et qualité
- HTML/CSS simples : restez cohérent avec le style existant.
- Accessibilité : privilégiez des contrastes suffisants, des balises sémantiques HTML et des textes alternatifs pour les images.
- Compatibilité : testez au moins sur un navigateur moderne (Chrome/Firefox/Edge/Safari récents).

## Processus de PR
- CI/CD : si des vérifications automatiques existent, assurez-vous qu'elles passent.
- Revues : soyez prêt à itérer selon les retours (noms, structure, capture d'écran supplémentaire, etc.).
- Squash/Rebase : il peut être demandé de "squash" vos commits pour garder un historique propre.

## Mise en place locale
Ce projet est statique :
-  Ouvrez simplement `index.html` dans votre navigateur.

## Licence
En contribuant, vous acceptez que votre contribution soit publiée sous la même licence que le dépôt (voir `README.md` pour les détails le cas échéant).

Merci !