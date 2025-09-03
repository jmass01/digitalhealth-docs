---
description: >-
  Cette page fournit des solutions rapides aux problèmes courants d'Odoo liés à
  la fabrication, à la configuration des nomenclatures, aux transferts de stock,
  à l'accès des utilisateurs ...
---

# Odoo

#### 🧭 Contexte

Cette page répertorie les problèmes les plus fréquents rencontrés par les utilisateurs travaillant avec Odoo dans un environnement de fabrication et de service. Elle sert de guide de référence rapide pour aider à identifier les problèmes et appliquer des solutions pratiques sans avoir besoin d'assistance technique. Que vous configuriez une nomenclature, gériez le stock ou traitiez un ordre de travail, cette page vous aidera à dépanner efficacement.

## Gestion des utilisateurs de service&#x20;

* L'utilisateur n'a pas le bon nom
* L'utilisateur n'a pas

## Gestion des stocks&#x20;

<details>

<summary>Aucune règle trouvée pour réapprovisionner un produit</summary>

Erreur : ![](https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FShKFRzFZBg5mlzdNDOye%2Fimage.png?alt=media\&token=d2815a59-2be5-4283-9e3b-ac9141a40025)

Vérifiez sur le produit s'il y a « Réapprovisionner à la commande (MTO) »

![](https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FnDaz7t8AkYCmKCQVwhFa%2Fimage.png?alt=media\&token=b7c415d3-2469-4a97-a317-c75fc25a6a14)

</details>

<details>

<summary>Problèmes avec les préparations de commandes </summary>

Le produit est dans le bon stock mais ne peut pas être réservé :

Un produit manque dans le mouvement

Le mauvais numéro de lot a été sélectionné :

Le système empêchera d'avoir une valeur négative.

</details>

## Réparation&#x20;

<details>

<summary>Il y a trop de produits dans le stock de réparation</summary>

Si en vérifiant l'emplacement de réparation vous voyez de telles prothèses, cela signifie que certaines des prothèses réparées n'ont soit pas été rendues, soit ne sont pas encore réparées.

</details>

<details>

<summary>Quantité insuffisante en réparation</summary>

![](https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2F4RP2TmorQPXBkGGSuv9S%2Fimage.png?alt=media\&token=244c327f-ef67-4fd7-8989-aa6ab1c4d61c)

Plusieurs raisons possibles :

* Le produit à réparer a été retiré du stock de réparation
* Le produit utilisé pour la réparation n'a pas été envoyé ou n'est pas en stock, veuillez vérifier avec votre gestionnaire de stock



</details>

## GPAO &#x20;

<details>

<summary>Attribut incorrect ou produit introuvable dans la config de la nomenclature</summary>

Pour résoudre ce problème, fermez d'abord le message et cliquez sur « ReConfigurer ». Dans un scénario où, par exemple, le Foot Sach 2.0 en « Beige » n'est pas disponible

<img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FIAvLZ6Gy7UTv3Ttn1XfQ%2Fimage.png?alt=media&#x26;token=ec637edd-04cc-4c80-8f5e-39d52237895b" alt="Attributes for the foot SACH 2.0" data-size="original">

Vous avez deux options : soit changer la sélection de couleur de la nomenclature pour une option disponible, soit mettre à jour la variante du produit pour inclure la couleur « Beige » si cela s'applique.

</details>

<details>

<summary>La variante du produit n'existe pas</summary>

Il se peut qu'une variante spécifique ait été archivée par erreur et que la configuration de la nomenclature ne puisse pas la trouver.&#x20;

Aller à [archivage-du-produit](../odoo/gestion-des-produits/archivage-du-produit "mention") pour savoir comment résoudre le problème.

</details>

## Problèmes administratifs&#x20;

<details>

<summary>Pas d'accès au formulaire utilisateur</summary>

Lors de la sauvegarde de la base de données, la pièce jointe est supprimée ou modifiée.

Pour résoudre ce problème, allez dans « Configuration » > Pièces jointes. Ensuite, sélectionnez tout et supprimez-les.

Cela résoudra l'erreur, vous pouvez régénérer le bundle d'assets si vous le souhaitez mais ce n'est pas nécessaire.

</details>

