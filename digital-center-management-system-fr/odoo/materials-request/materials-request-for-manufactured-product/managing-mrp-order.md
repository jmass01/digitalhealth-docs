# Gestion des ordres MRP

{% hint style="info" %}
## Rôles recommandés : P\&O, Opérateur d'atelier
{% endhint %}

## **🧭** Contexte&#x20;

Ce flux doit être suivi **après la création de la configuration de la nomenclature (BoM)**. &#x20;

## 🔄 Flux étape par étape&#x20;

### Création de l'ordre MRP

La création de l'ordre MRP se fait à partir du formulaire de la configuration de BoM précédente.&#x20;

Une fois que vous avez vérifié les composants à consommer et défini les opérations dans la configuration de la BoM, vous pouvez procéder à la création d'un ordre de fabrication en cliquant sur le bouton "Créer un ordre MRP" situé dans le ruban supérieur.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FnKsNFoZSP8oQGBzgrkPq%2Fimage.png?alt=media&#x26;token=cb59da44-8ae7-4f22-b450-262a18062e06" alt=""><figcaption></figcaption></figure>

Cette action lance la création d'un ordre de travail qui inclut tous les composants nécessaires à la consommation et s'ouvrira dans une fenêtre contextuelle. L'ordre de travail démarre à l'état brouillon.

{% hint style="info" %}
Même si vous fermez la fenêtre contextuelle sans enregistrer, l'ordre MRP a été créé
{% endhint %}

### Accéder à l'ordre MRP

{% tabs %}
{% tab title="Depuis la configuration de la BoM" %}
Après la création directe, vous devriez toujours être sur la configuration de la BoM ; vous pouvez trouver dans le formulaire le lien direct vers l'ordre de fabrication.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2F1gslXyW7coftV1k6Trmi%2Fimage.png?alt=media&#x26;token=c76913d8-cb7a-483d-9532-ff85589b855e" alt=""><figcaption></figcaption></figure>

&#x20;
{% endtab %}

{% tab title="Via la gestion du SU" %}
Sur la page d'accueil, allez à l'icône « Gestion des utilisateurs de service ».&#x20;

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FwgYqssYNXVtjPhYKKBCa%2Fimage.png?alt=media&#x26;token=e2aac634-e10d-49ba-b5c1-4b7793532432" alt=""><figcaption></figcaption></figure>

Vous pouvez voir une liste de tous les SU[^1]s ici. Utilisez la barre de recherche en haut pour trouver un bénéficiaire de service par son nom ou SU[^1] ID. Veuillez vous assurer de sélectionner la bonne option.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FqXqX10GKFUpZ6yfM8R8Q%2Fimage.png?alt=media&#x26;token=05d8cde9-c530-457f-91aa-86e689d6282a" alt=""><figcaption></figcaption></figure>

Dans le formulaire SU, vous trouverez un bouton intitulé «**MRP Production** ». En cliquant dessus, toutes les ordres de fabrication associées à ce Service User spécifique s'ouvriront.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FS01b7vaSf3ePt9ZKhwlp%2Fimage.png?alt=media&#x26;token=8e0471ce-5f15-4335-9642-965f56d31f79" alt=""><figcaption></figcaption></figure>


{% endtab %}

{% tab title="Via l'application Inventaire" %}
Sur la page d'accueil, allez à l'icône « Manufacturing ».

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FtXcdYty56UzWoCp3mxbq%2Fimage.png?alt=media&#x26;token=8fe5597a-ec02-4689-af85-a7abaa1e217e" alt=""><figcaption></figcaption></figure>

Vous pouvez voir ici une liste de tous les Ordres de Fabrication. Utilisez la barre de recherche en haut pour trouver le bon Ordre de Fabrication par sa référence, par le nom du patient, SU[^1] ID ... Veuillez vous assurer de sélectionner la bonne option.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2F2NQNb4AjLxVmBf7fQxlC%2Fimage.png?alt=media&#x26;token=308cab1c-96c7-4aff-aeba-b26b63fdc9b7" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

### Confirmer un ordre MRP

Il est important de noter que selon votre rôle de sécurité, vous pouvez ne pas avoir l'autorisation de confirmer l'ordre MRP. En général, seuls les physiothérapeutes, les orthésistes ou le personnel autorisé peuvent confirmer cet ordre MRP, garantissant que le processus de fabrication se déroule précisément et conformément au plan.

_Techniquement : si l'utilisateur n'a pas le rôle (group\_mrp\_manager), il ne verra pas le bouton "Confirmer" et ne pourra effectuer aucune action liée à la confirmation de la planification des ressources de fabrication (MRP). Seuls les utilisateurs disposant de ce rôle spécifique auront le bouton "Confirmer" activé._

Avant de procéder à la confirmation du MRP, ces utilisateurs autorisés doivent s'assurer que tous les produits destinés à la consommation sont soigneusement vérifiés pour en garantir l'exactitude. Cela inclut la vérification des quantités et la résolution de tout problème tel que les produits manquants.

&#x20;Si des ajustements sont nécessaires, l'utilisateur peut modifier les lignes existantes ou en créer de nouvelles en suivant le même processus que pour la configuration de la BoM décrit ici.

Une fois que tous les détails des produits sont corrects, l'utilisateur peut procéder à la confirmation du MRP en cliquant sur le bouton "Confirmer".

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FWoFVXvadagrYnwNQdlIF%2Fimage.png?alt=media&#x26;token=aa77b8b5-ed64-472f-b255-fefc800fa88e" alt=""><figcaption></figcaption></figure>

Après confirmation, le système réservera le stock nécessaire pour cette commande. En général, les produits sont disponibles dans le stock principal mais peuvent devoir être transférés à l'atelier.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FJFijfWGTr4Rd1YcsDZO1%2Fimage.png?alt=media&#x26;token=ff744adf-673c-4d21-8210-514c94e9812e" alt=""><figcaption></figcaption></figure>

Par défaut, le système génère un ordre de transfert du stock principal vers l'atelier, qui peut être consulté directement depuis l'ordre MRP ou via le module Inventaire.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2F8zXyBRp6tIKehveDTmJE%2Fimage.png?alt=media&#x26;token=886b4067-38bf-4975-8c17-faa538eaeb2f" alt=""><figcaption></figcaption></figure>

De plus, si le module Achats est correctement configuré, la confirmation de la commande d'achat (PO) déclenchera la création de commandes d'achat auprès des fournisseurs. Pour plus de détails sur ce processus, référez-vous aux directives spécifiques fournies.

### 🗺️ Aperçu visuel&#x20;

Graphique Mermaid à faire

## Et ensuite ?&#x20;

Après la finalisation de l'ordre de fabrication, l'étape suivante consiste à livrer la prothèse au bénéficiaire du service pour que le gestionnaire de stock et le P\&O attendent cette affectation de stock pour le traitement de l'ordre de fabrication.

[^1]: Fournisseur de service
