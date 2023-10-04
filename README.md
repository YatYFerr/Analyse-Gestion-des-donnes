## Optimisation de la gestion des données d'un marchand de vin

Deux exports travaillés : 
- un export de l’ERP contenant les références produit, leur prix de vente et leur état de stock,
- un export d’une table de l’outil de CMS contenant les informations des produits
commercialisés en ligne (nom, description, nombre de ventes...).

L’export issu de la boutique en ligne contient le nombre de ventes pour chaque
produit depuis sa mise en ligne, il ne permet pas d’analyser l'évolution des
ventes dans le temps.

Un tableau Excel a été créé pour permettre d’établir le lien entre la référence du produit dans l’ERP
(product_id) et la référence du même produit dans la base de la boutique en ligne (SKU).

Analyses effectuées sur:

- Le chiffre d’affaires par produit, ainsi que le total du chiffre d’affaires réalisé
- Analyse du CA afin de détecter d’éventuelles valeurs aberrantes, de les listeret d’en faire une représentation graphique pour plus de lisibilité.
