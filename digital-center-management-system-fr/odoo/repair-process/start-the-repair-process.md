# Démarrer le processus de réparation

{% hint style="info" %}
### Rôles recommandés : Ouvrier d'atelier / Magasinier
{% endhint %}

## **🧭** Contexte

Cette étape se déroule **après que l'ordre de réparation a été confirmé**. À ce stade, tous les détails de la réparation sont déjà renseignés. Le système réservera les produits nécessaires à la réparation. Ensuite, le **Magasinier** prépare ces articles et les remet au **Technicien**. Une fois les matériaux prêts, le technicien peut commencer la réparation. Cette partie du processus garantit que tout ce qui est nécessaire à la réparation est disponible et prêt à être utilisé.

## 🔄 Flux étape par étape

### Accéder à l'ordre de réparation

Si vous **n'êtes pas déjà dans un ordre de réparation**, suivez les étapes ci-dessous pour en accéder à un.\
Si vous êtes **déjà dans un ordre de réparation existant**, vous pouvez ignorer cette partie et passer à l'étape suivante.

{% tabs %}
{% tab title="Via la gestion du SU" %}
Sur la page d'accueil, allez à l'icône « Gestion des utilisateurs de service ».

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FwgYqssYNXVtjPhYKKBCa%2Fimage.png?alt=media&#x26;token=e2aac634-e10d-49ba-b5c1-4b7793532432" alt=""><figcaption></figcaption></figure>

Vous pouvez voir une liste de tous les SU[^1]ici. Utilisez la barre de recherche en haut pour trouver un patient par son nom ou SU[^1] ID. Veuillez vous assurer de sélectionner la bonne option.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FqXqX10GKFUpZ6yfM8R8Q%2Fimage.png?alt=media&#x26;token=05d8cde9-c530-457f-91aa-86e689d6282a" alt=""><figcaption></figcaption></figure>

Dans le formulaire de l'utilisateur de service (SU), vous trouverez un onglet intitulé **« Ordres de réparation »**. L'ouverture de cet onglet affichera la liste de tous les ordres de réparation liés à ce SU spécifique.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FE3nGMbdvRWEOCVkXtMau%2Fimage.png?alt=media&#x26;token=c1a3e4c9-c5e9-448c-885c-a4db31571469" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Via l" %}
Sur la page d'accueil, allez à l'icône « Réparations ».

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FQlh5Lr5TNtQF9QvOoEVa%2Fimage.png?alt=media&#x26;token=3de536ee-71ac-4d21-8c3c-6d0f0f7ee8d1" alt=""><figcaption></figcaption></figure>

Vous pouvez voir une liste de tous les ordres de réparation ici. Utilisez la barre de recherche en haut pour trouver la bonne réparation par sa référence, par le produit à réparer, SU[^1] ID ... Veuillez vous assurer de sélectionner la bonne option.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2Fq4cvrChkM16WE592Uwny%2Fimage.png?alt=media&#x26;token=480441bb-b118-4e7e-a0e3-ca651668b91f" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

### Démarrer l'ordre de réparation

Pour démarrer le processus de réparation dans Odoo, cliquez sur "Démarrer la réparation". Si une fenêtre d'erreur apparaît, référez-vous à \[[ce guide](../../depannage-et-faq/)].

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FbnKBIIhV3k5cFmGxCBcX%2Fimage.png?alt=media&#x26;token=b9fba6e2-167a-4ee5-ad82-0f9b8c2bcede" alt=""><figcaption></figcaption></figure>

Si la configuration est correcte, tous les composants de la liste devraient être dans l'état "En attente d'un autre mouvement", indiquant qu'un transfert est en cours pour réapprovisionner le stock de réparation.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FkCayqH1ovZJMkCz5LUVr%2Fimage.png?alt=media&#x26;token=b4d63360-f343-40c4-8a96-4752b3ad2ab7" alt=""><figcaption></figcaption></figure>

L'étape suivante implique le magasinier, qui doit se rendre dans "Réapprovisionner la réparation" dans le module Inventaire pour valider le transfert une fois que l'utilisateur a récupéré les composants. Cette étape suit le processus standard de mouvement de stock, que vous pouvez consulter en détail \[ici].

### Valider l'ordre de réapprovisionnement

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FJJp8IhGJsgHIcX0tkjQA%2Fimage.png?alt=media&#x26;token=6153794e-f701-4432-9d8f-0d2d4a273243" alt=""><figcaption></figcaption></figure>

Une fois le transfert validé, le retour à l'ordre de réparation montrera que tous les composants sont maintenant dans l'état "Disponible", avec leurs quantités réservées mises à jour.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FcVIFY0bRBfsw8G8qvlom%2Fimage.png?alt=media&#x26;token=a6e71df7-0cdc-479c-8e33-931fb3fe2003" alt=""><figcaption></figcaption></figure>

### Terminer la réparation

Lorsque la réparation est terminée, cliquez simplement sur "Terminer la réparation". Le processus de réparation est maintenant finalisé, et le stock a été mis à jour en conséquence dans Odoo.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FbFl0qxg6uaAyIAoZLTDT%2Fimage.png?alt=media&#x26;token=66ff0c39-0da1-4edc-bbb2-ce52c52e08b0" alt=""><figcaption></figcaption></figure>

### 🗺️ Aperçu visuel

\{% @mermaid/diagram content="graph LR A\[Access the Repair Order] --> B\[Start the Repair] B --> C\[System Reserves the Product] C --> D\[Storekeeper Prepares Items from Stock] D --> E\[Items Handed to Technician] E --> F\[Perform the Repair] F --> G\[End the Repair]" %\}

## Et ensuite ?

Une fois la réparation terminée, l'étape suivante dépendra de la façon dont votre centre est configuré :

* Si votre centre utilise un **Contrôle Qualité** processus, le produit réparé passera par un contrôle qualité avant de pouvoir être livré. Cette étape aide à assurer que l'article répond aux normes requises.
* S'il n'y a **pas d'étape de Contrôle Qualité**, vous pouvez passer directement à la **Livraison du produit réparé** au Prestataire de service.

Les deux options font partie des étapes finales pour s'assurer que le Prestataire de service reçoit un article fonctionnel et correctement tracé.

[^1]: Fournisseur de service
