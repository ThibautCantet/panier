# Panier

## Objectifs
Les objectifs de ce kata sont :
- de faire du TDD
- de la modélisation


## Fonctionnalités à développer
- Calculer le prix total d'un panier : total des lignes du panier + frais de port
- Calculer le prix des lignes séparément des frais de port selon les conditions ci-dessous

## Règles de calcul sur les frais de port
Si la somme des lignes est inférieure à 20€ alors les frais de port seront de 3€

Si la somme des lignes est supérieure à 20€ alors les frais de port seront gratuits

Mais avec la nouvelle lois Darcos, les frais de ports pour les livres sont forcément appliqués si la commande concerne des livres neufs dont le montant est inférieur à 35€. Le montant des frais de port sera de 3€ (minimum défini par la loi)

Attention, cette règle s'applique si la commande est mixte.
