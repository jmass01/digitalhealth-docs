# Créer un produit sans variantes

Un produit simple est créé sans variantes. Dans ce cas, un Produit (product.template) correspond à une Varainte (product.product)\
Exemples de tels produits : bas pour femmes, plâtre de Paris - poudre, etc...\
Pour ces produits, nous devons définir seulement quelques éléments :\


<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FcOggeZCWrvJXFKSStLnN%2Fimage.png?alt=media&#x26;token=33107a7b-998e-4413-bcb1-e833f4d606cb" alt=""><figcaption></figcaption></figure>

1. La sélection des cases à cocher pour acheter ou vendre influencera la visibilité de ce produit dans différentes sections du système Odoo.
2. Type de produit : Cette catégorisation aide à comprendre comment un produit est utilisé ou consommé :

* **Service**: Un produit immatériel qui implique l'exécution de tâches ou d'activités pour un client.
* **Consommable**: Un produit destiné à être consommé ou épuisé rapidement lors de son utilisation.
* **Stockable**: Un produit qui peut être stocké et utilisé sur une longue période sans consommation immédiate.



3\. - Catégorie de produit - obligatoire, permet au produit d'être davantage configuré et groupé

4\. - Référence interne - ou code, utilisé pour retrouver le produit plus rapidement

5\. - Prix de vente - est le prix de base qui sera affiché lors de la vente ou de la facturation de cet article

6\. - Taxes client - lors de la vente du produit, cette taxe sera appliquée par défaut (peut être modifiée par les règles de position fiscale)

7\. - Unités de mesure, Unité de mesure d'achat - l'unité de mesure est utilisée pour ce produit en interne, tandis que l'unité de mesure d'achat est/peut être utilisée lors de l'achat du produit.\
par exemple, pour le plâtre de Paris l'unité de mesure est le kilogramme, mais il peut être acheté en sac de 50 kg –
