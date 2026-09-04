# 11rei-photos-blog / 11rei-photos — conventions de nommage

Ce dépôt contient les photos utilisées sur le site du 11e REI. Pour garder les choses lisibles au fil des ajouts, chaque photo suit l'une des conventions ci-dessous selon son usage.

## Portraits individuels (`11rei-photos`)

- **Portrait principal** : `<identifiant>.jpg`
  Exemple : `danneskjold-henri.jpg`
- **Photos supplémentaires** (jusqu'à 2) : `<identifiant>-2.jpg`, `<identifiant>-3.jpg`
  Chargées automatiquement par les pages recensement/thématiques si elles existent (pas besoin de les déclarer ailleurs).
- `<identifiant>` = le champ `Identifiant` de `verif_data.xlsx`, pas le nom complet.

## Photos de sépulture (`11rei-photos-blog`)

- `tombe-<identifiant>.jpg`
  Exemple : `tombe-ler-alphonse.jpg`
  Même `<identifiant>` que le portrait de la même personne.

## Illustrations d'un article (`11rei-photos-blog`)

- `blog-<slug-article>-N.jpg` (N commence à 2, la 1ʳᵉ image d'un article n'a pas de suffixe)
  Exemple : `blog-danneskjold-henri-2.jpg`, `blog-morts-du-11e-rei-2.jpg` (photo de couverture)

## Photos de contexte familial (`11rei-photos`)

- `famille-<nom>.jpg` (+ `1`, `2`, `3`... pour plusieurs photos de la même famille, sans tiret avant le chiffre)
  Exemple : `famille-freund-mechel-baruch.jpg`, `famille-freund-mechel-baruch1.jpg`
  Utilisées dans le corps d'une page recensement (ex. `recensement-volontaires-juifs.html`), pas via le mécanisme automatique des portraits.

## Avant de supprimer une photo

Une photo peut être utilisée de 3 façons différentes, pas toujours visibles dans le code d'une seule page :
1. Référencée directement par son URL complète dans une page HTML ou un article.
2. Construite automatiquement à partir de l'`Identifiant` d'une personne (portraits et photos supplémentaires).
3. Utilisée uniquement sur une page encore hébergée sur Google Sites (pas encore migrée).

**Avant toute suppression**, vérifier les 3 cas — un fichier qui semble inutilisé dans le dépôt migré peut encore servir ailleurs.

---
*Dernière mise à jour : voir l'historique Git de ce fichier.*
