# Qu'est-ce qu'un attribut de produit

L'attribut de produit nous aide à définir plusieurs variantes de produit avec des codes produit générés selon une règle spécifiée, et à les gérer à partir d'un seul produit (modèle).\
Le produit peut être configuré en utilisant plusieurs attributs, et en autorisant des valeurs d'attribut spécifiées pour ce produit.

Pour accéder à la liste des attributs de produit disponibles, (gestionnaire de stock) allez à :\
**Inventaire -> Configuration -> Produits -> Attributs**\


<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FPx9Y64cSFSqWUZQtZg44%2Fimage.png?alt=media&#x26;token=c6e2050e-aab6-4827-8857-6769067ce8c9" alt="" width="560"><figcaption></figcaption></figure>

Lors de la création d'un nouvel attribut, vérifiez s'il existe déjà ou s'il est utilisé...

* 1\. Nom de l'attribut - doit être unique et pas trop long (car il sera affiché dans le nom complet du produit...
* 2\. code de l'attribut - non requis, car il peut ajouter une partie du code au code du produit (variante). testez avant utilisation !
* 3\. type d'affichage - sélectionnez le comportement / comment il est affiché dans les différentes parties d'odoo
* 4\. Mode de création des variantes&#x20;
  * Instantanément - lorsque le produit est créé et que l'attribut et les valeurs sont assignés, odoo créera toutes les variantes du produit
  * Dynamiquement - odoo créera une variante de produit seulement lorsqu'elle sera utilisée dans une ligne de commande client/frais pour l'attribut sélectionné
  * Jamais - les variantes de produit ne seront jamais créées pour aucune de ces valeurs d'attribut

Important - cette option ne peut pas être modifiée une fois que le premier produit est configuré avec cet attribut/ces valeurs

* 5\. Valeurs de l'attribut - configurez toutes les valeurs possibles -\
  \- note : lors de la configuration d'un produit, vous pouvez utiliser toutes ou seulement certaines valeurs d'attribut\
  ![](https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FtKz8sApMoMH5qFCPEFGH%2Fimage.png?alt=media\&token=1e660d6b-0540-4856-974a-d55e58a7336b)\

  * 1\. le nom de la VALEUR de l'attribut doit être unique
  * 2\. la partie du code ajoutée au code produit pour cette valeur
  * 3\. Est une valeur personnalisée - si cochée, il sera nécessaire à chaque fois de saisir une valeur personnalisée
