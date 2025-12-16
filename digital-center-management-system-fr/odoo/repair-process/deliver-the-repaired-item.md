# Livrer l’élément réparé

{% hint style="info" %}
### Rôles recommandés : Atelier / Magasinier
{% endhint %}

## **🧭** Contexte

Une fois le processus de réparation terminé, l'étape suivante consiste à s'assurer que l'article réparé est retourné à l'Utilisateur du Service. Cette étape se concentre sur la création et la validation de l'ordre de livraison afin que l'article puisse être officiellement remis. Documenter cette étape garantit la traçabilité, confirme que le cycle de réparation est correctement clôturé et fournit à l'Utilisateur du Service le produit réparé de manière structurée et transparente.

## 🔄 Flux étape par étape

### Accéder à l'ordre de réparation

Si vous **n'êtes pas déjà dans un ordre de réparation**, suivez les étapes ci-dessous pour y accéder.\
Si vous **êtes déjà dans un ordre de réparation existant**, vous pouvez passer cette partie et aller à l'étape suivante.

{% tabs %}
{% tab title="Via la gestion de l" %}
Sur la page d'accueil, allez à l'icône « Gestion des Utilisateurs du Service ».

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FwgYqssYNXVtjPhYKKBCa%2Fimage.png?alt=media&#x26;token=e2aac634-e10d-49ba-b5c1-4b7793532432" alt=""><figcaption></figcaption></figure>

Vous pouvez voir une liste de tous les US[^1]ici. Utilisez la barre de recherche en haut pour trouver un patient par son nom ou US[^1] ID. Veuillez vous assurer de sélectionner la bonne option.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FqXqX10GKFUpZ6yfM8R8Q%2Fimage.png?alt=media&#x26;token=05d8cde9-c530-457f-91aa-86e689d6282a" alt=""><figcaption></figcaption></figure>

Dans le formulaire de l'Utilisateur du Service (US), vous trouverez un onglet intitulé **« Ordres de réparation »**. L'ouverture de cet onglet affichera la liste de tous les ordres de réparation liés à cet US spécifique.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FE3nGMbdvRWEOCVkXtMau%2Fimage.png?alt=media&#x26;token=c1a3e4c9-c5e9-448c-885c-a4db31571469" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Via l" %}
Sur la page d'accueil, allez à l'icône « Réparations ».

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FQlh5Lr5TNtQF9QvOoEVa%2Fimage.png?alt=media&#x26;token=3de536ee-71ac-4d21-8c3c-6d0f0f7ee8d1" alt=""><figcaption></figcaption></figure>

Vous pouvez voir une liste de tous les ordres de réparation ici. Utilisez la barre de recherche en haut pour trouver la bonne réparation par sa référence, par le produit à réparer, US[^1] ID ... Veuillez vous assurer de sélectionner la bonne option.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2Fq4cvrChkM16WE592Uwny%2Fimage.png?alt=media&#x26;token=480441bb-b118-4e7e-a0e3-ca651668b91f" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

### Créer l'article de livraison

Sur le formulaire de réparation, cliquez sur le **bouton « Livrer l'article »** . Cela créera automatiquement un **Bon de livraison** pour gérer le retour du produit réparé à l'Utilisateur du Service.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FB8H8cA2EocmIl688jjpQ%2Fimage.png?alt=media&#x26;token=a9fe8fb7-47f9-4ceb-ac5b-0253f3a6265e" alt=""><figcaption></figcaption></figure>

Le bon de livraison est maintenant créé et marqué comme prêt, il apparaîtra dans le formulaire de l'Utilisateur du Service (US) sous l'onglet « Réception/Expédition » (Stock Picking). Cet enregistrement de transfert aura un nom spécifique qui inclut généralement « RMA-OUT », indiquant qu'il s'agit d'une réparation (RMA) envoyée.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FvOut5SktH01LgfJUgj3H%2Fimage.png?alt=media&#x26;token=d1746c94-9b2c-4b61-955d-043d2ca8005e" alt=""><figcaption></figcaption></figure>

Vous pouvez également trouver le même mouvement de stock dans le module Inventaire sous le type d'opération « Livraison RÉPARÉE ».

<div align="left"><figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2Fe0fMbarsUAb7BvV0r8lH%2Fimage.png?alt=media&#x26;token=4e1eadbb-858d-4f53-9d24-93b7a5f90e1e" alt=""><figcaption></figcaption></figure></div>

Une fois le Stock Picking ouvert, le processus suit les mêmes étapes que pour tout autre transfert. Cliquez simplement sur « Auto-validation », et la quantité correcte sera définie automatiquement.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FFNPtIjJEDLybiKX7dlpC%2Fimage.png?alt=media&#x26;token=a13960e9-fe0c-4376-95a0-31dc661c0c9d" alt=""><figcaption></figcaption></figure>

Si le produit a un numéro de lot, vérifiez que le bon numéro est attribué avant de poursuivre. Ensuite, cliquez sur le bouton « Valider » pour mettre à jour le statut en Terminé.

Pour plus de détails sur la gestion des transferts de stock, veuillez vous référer à ce [Guide](../gestion-des-stocks/).

### 🗺️ Aperçu visuel

\{% @mermaid/diagram content="graph TD A\[Open the Repair Order form] --> B\[Click Deliver Item button] B --> C\[Delivery Order is created and marked as Ready] C --> D\["Delivery appears in SU form under Stock Picking tab(RMA-OUT)"] C --> E\[Delivery also visible in Inventory > Deliver REPAIRED] D --> F\[Open the Delivery Order] E --> F F --> G\[Click Auto-Validate] G --> H{Does the product have a Lot Number} H -- Yes --> I\[Verify Lot Number is correct] H -- No --> J\[Proceed to validation] I --> K\[Click Validate to mark as Done] J --> K " %\}

## Et ensuite ?

Une fois la livraison validée et terminée, cela confirme que le patient a reçu son produit réparé. Le système mettra automatiquement à jour le stock pour refléter cela. Cette étape marque la fin officielle du processus de réparation.

[^1]: Prestataire de service
