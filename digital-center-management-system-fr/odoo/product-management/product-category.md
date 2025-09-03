# Catégorie de produit

Les catégories de produits jouent un rôle crucial dans l'organisation et la gestion efficaces des stocks.

Les catégories de produits aident à déterminer la façon dont les stocks sont évalués. Chaque catégorie peut se voir attribuer une méthode d'évaluation spécifique telle que le prix standard ou FIFO (First In, First Out), ce qui influence la façon dont le coût des marchandises vendues (COGS) et l'évaluation des stocks sont calculés.

<div align="left"><figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FC6EVnr39OsdWCZ6C0Kzy%2Fimage.png?alt=media&#x26;token=752b0bfe-5c2f-4cd7-a5aa-43190265c21d" alt=""><figcaption></figcaption></figure></div>

Les catégories de produits facilitent la logistique et l'organisation efficaces. Elles permettent de regrouper les produits en fonction de caractéristiques similaires, telles que le type, la fonction ou l'utilisation. Ce regroupement simplifie les recherches d'inventaire, les rapports et garantit que les produits sont stockés et gérés de manière logique.

Dans l'ensemble, les catégories de produits dans Odoo sont fondamentales pour structurer la gestion des stocks, optimiser la logistique, faciliter une évaluation précise, permettre des rapports détaillés et automatiser les flux de travail.

&#x20;

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2F7asJh3ims16lB4vOiVTp%2Fimage.png?alt=media&#x26;token=38ba51c0-6bad-4030-9b40-a059d4645974" alt=""><figcaption></figcaption></figure>

* 1\. Nom de la catégorie , obligatoire , ne pas utiliser le nom de la catégorie parent il sera généré
* 2\. Catégorie parente - sélectionnez la catégorie parente appropriée
* 3\. Routes - routes de stock appliquées à cette catégorie, et à toutes les sous-catégories\
  Le total des routes est calculé en fonction de toutes les routes sélectionnées pour cette catégorie et pour toutes les catégories parentes
* 4\. Stratégie de retrait forcé - sélectionnable par catégorie, habituellement il y aura
  * FIFO - Premier entré Premier sorti
  * LIFO - Dernier entré Premier sorti
  * FEFO - Premier à expirer Premier sorti (uniquement si nous utilisons des dates d'expiration)
* 5\. Stock négatif - en général, il ne devrait pas être utilisé...
* 6\. La méthode de valorisation détermine comment le coût du produit est calculé et enregistré à des fins d'évaluation des stocks, les options disponibles sont :
  * Prix standard - le prix défini sur le produit est utilisé pour l'évaluation
  * FIFO - Premier entré Premier sorti - l'évaluation des stocks est calculée dans l'ordre des réceptions de marchandises avec les prix appropriés
  * AVCO - Coût moyen - chaque réception impacte le recalcul du prix de coût moyen
* 7\. Évaluation des stocks (déclencheur)\
  \- Manuel - manuellement (déclencher périodiquement le calcul de (ré)évaluation des stocks)\
  \- Automatique - chaque mouvement de stock crée automatiquement le calcul de la couche d'évaluation en temps réel
* 8\. Propriétés comptables - définissez-les selon les besoins comptables, utilisées pour enregistrer la valorisation des mouvements de stock en comptabilité
* 9\. OPTIONNEL - si le centre utilise une langue autre que l'anglais, cela sert à afficher le nom de la catégorie en anglais pour faciliter le support et l'analyse des données
* 10\. - Vérifier les produits dans cette catégorie - ATTENTION - UNIQUEMENT les produits dans CETTE catégorie, pas les sous-catégories !!
* 11\. Règles de rangement (putaway) - rarement utilisées
