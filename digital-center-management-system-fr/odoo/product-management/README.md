# Gestion des produits

Les données principales les plus importantes dans Odoo sont les produits.\
Il est très important de connaître et de comprendre la différence entre Produit (modèle product.template) et Variante (modèle : product.product)\
Les Produits et Variantes sont accessibles depuis la plupart des éléments du menu principal d’Odoo tels que : Ventes, Stock, Facturation, Achats, GMAO...\
L’élément de menu Produit (modèle product.template) sert de menu principal de configuration.\
Lorsqu’un produit peut être configuré avec des attributs et des valeurs préconfigurées, lors de l’enregistrement il créera le nombre approprié de Variantes\
Exemple : Nous configurons un produit : T-shirt, puis nous définissons des attributs\
\- Taille, avec les valeurs : S, M, L, XL, XXL\
\- Couleur : avec les valeurs : Blanc, Noir, Bleu\
à l’enregistrement du Produit, il y aura 20 Variantes (produit cartésien des valeurs d’attribut...\
L’utilisation appropriée des attributs et des valeurs d’attribut est importante pour la bonne configuration des modèles de nomenclature (BoM) de la GMAO ainsi que pour la gestion du catalogue central des produits.\
Conseils utiles

* Si le nom du produit contient l’un des attributs habituels : Petit, Enfant, Adulte, Gauche, Droit, etc., il devrait être configuré avec des variantes
