---
description: Comment confirmer l'ordre de fabrication
---

# Validation de l'ordre de fabrication

{% hint style="info" %}
Rôles recommandés : P&0&#x20;
{% endhint %}

## **🧭** Contexte&#x20;

Cette étape a lieu après **que toutes les étapes d'ordre de travail ont été validées avec succès**, et **tous les composants utilisés sont désormais disponibles à l'emplacement de l'atelier**.&#x20;

Le processus de fabrication est terminé, et le système est prêt pour **l'étape finale de l'Ordre de Fabrication** pour confirmer l'achèvement de la production.

## 🔄 Flux étape par étape&#x20;

### Accéder à l'ordre de fabrication

{% tabs %}
{% tab title="Via la gestion des SU" %}
Sur la page d'accueil, allez à l'icône « Service User Management ».

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FwgYqssYNXVtjPhYKKBCa%2Fimage.png?alt=media&#x26;token=e2aac634-e10d-49ba-b5c1-4b7793532432" alt=""><figcaption></figcaption></figure>

Vous pouvez voir une liste de tous les SU[^1]ici. Utilisez la barre de recherche en haut pour trouver un patient par son nom ou SU[^1] ID. Veuillez vous assurer de sélectionner la bonne option.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FqXqX10GKFUpZ6yfM8R8Q%2Fimage.png?alt=media&#x26;token=05d8cde9-c530-457f-91aa-86e689d6282a" alt=""><figcaption></figcaption></figure>

Dans le formulaire SU, vous trouverez un bouton intitulé «**MRP Production** ». En cliquant dessus, toutes les ordres de fabrication associées à ce Service User spécifique s'ouvriront.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FS01b7vaSf3ePt9ZKhwlp%2Fimage.png?alt=media&#x26;token=8e0471ce-5f15-4335-9642-965f56d31f79" alt=""><figcaption></figcaption></figure>


{% endtab %}

{% tab title="Via l'application Manufacturing" %}
Sur la page d'accueil, allez à l'icône « Manufacturing ».

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FtXcdYty56UzWoCp3mxbq%2Fimage.png?alt=media&#x26;token=8fe5597a-ec02-4689-af85-a7abaa1e217e" alt=""><figcaption></figcaption></figure>

Vous pouvez voir ici une liste de tous les Ordres de Fabrication. Utilisez la barre de recherche en haut pour trouver le bon Ordre de Fabrication par sa référence, par le nom du patient, SU[^1] ID ... Veuillez vous assurer de sélectionner la bonne option.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2F2NQNb4AjLxVmBf7fQxlC%2Fimage.png?alt=media&#x26;token=308cab1c-96c7-4aff-aeba-b26b63fdc9b7" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

### Valider l'ordre de fabrication

Pour valider un Ordre de Fabrication (OF), cliquez sur le bouton « Marquer comme terminé ». Plusieurs vérifications sont effectuées lors de la validation :

1.  Si un quelconque ordre de travail est encore ouvert, une fenêtre contextuelle vous informera de terminer d'abord tous les ordres de travail.\


    <figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FXSK72PgIKpeEzCkSvHbU%2Fimage.png?alt=media&#x26;token=08a97def-a26e-4f1b-955e-b698075e2ede" alt=""><figcaption></figcaption></figure>
2.  Si la quantité consommée diffère, une fenêtre contextuelle vous avertira. Après examen, vous pouvez soit « Confirmer » soit « Revoir la consommation » plus en détail\


    <figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FABUtnDEndPBb8ovACkJZ%2Fimage.png?alt=media&#x26;token=16c2d4e0-df52-46f3-ab54-ca28d6d6f338" alt=""><figcaption></figcaption></figure>
3.  Si aucun numéro de série n'a été attribué, une fenêtre contextuelle vous invitera à fournir un numéro de lot/numéro de série.\
    \


    <figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FLPY9qyZ6asqIHT1ANPKZ%2Fimage.png?alt=media&#x26;token=25dbc19b-2d4a-4219-889d-b2b658cc2b6b" alt=""><figcaption></figcaption></figure>

Pour attribuer un numéro de lot/numéro de série, retournez à l'OF, créez un nouveau lot manuellement ou cliquez sur le bouton + pour ajouter le numéro de série, puis revalidez l'enregistrement.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FkDGvjG9Xg23LuaOhqfa5%2Fimage.png?alt=media&#x26;token=aa5697e7-5cb7-432d-bcd9-863e948eb9cc" alt=""><figcaption></figcaption></figure>

Après résolution de tout problème, le statut de l'OF passera à « Terminé » et deviendra en lecture seule.&#x20;

Le produit fabriqué entrera en stock.&#x20;

### 🗺️ Aperçu visuel&#x20;

Graphique Mermaid à faire

## Et après ?&#x20;

Après avoir finalisé l'ordre de fabrication, l'étape suivante est de livrer la prothèse au Service User.

[Cliquez ici pour accéder à cette action ](../remise-du-produit-a-lutilisateur-de-service)



[^1]: Prestataire de service
