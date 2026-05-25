# /commit

Sauvegarde l'état actuel du workspace dans Git.

## Comportement

1. Afficher les fichiers modifiés/ajoutés avec `git status`
2. Stager tous les changements avec `git add -A` (`.gitignore` protège `.env`)
3. Générer un message de commit court et descriptif en français, basé sur les changements détectés
4. Effectuer le commit
5. Confirmer le succès avec le hash du commit

## Règles

- Ne jamais committer `.env` ou tout fichier listé dans `.gitignore`
- Message de commit en français, concis (moins de 72 caractères)
- Format : `type: description courte` — ex: `ajout: commande /commit`, `mise à jour: contexte HISTORY.md`
- Si aucun changement détecté, le signaler sans créer de commit vide
