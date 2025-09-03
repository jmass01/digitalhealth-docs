# Créer la demande de réparation

{% hint style="info" %}
## Rôles recommandés : P\&O, Ouvrier d'atelier
{% endhint %}

## **🧭** Contexte&#x20;

Cette étape a lieu **après que le produit a été reçu pour réparation** et correctement enregistré dans le système. À ce stade, l'article est physiquement disponible sur le lieu de réparation, et le processus de réparation peut commencer. Le flux suivant se concentre sur la **création et la configuration de l'ordre de réparation**, qui définira le travail à effectuer et les composants impliqués. Que vous lanciez la réparation depuis le **formulaire d'Utilisateur du Service** ou directement depuis la **vue liste des réparations**, ce processus garantit que la réparation est correctement suivie et alignée avec les mouvements d'inventaire.

## 🔄 Flux étape par étape&#x20;

### Création de l'ordre de réparation

{% tabs %}
{% tab title="Via la gestion SU" %}
Sur la page d'accueil, allez à l'icône "Gestion des utilisateurs du service".

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FwgYqssYNXVtjPhYKKBCa%2Fimage.png?alt=media&#x26;token=e2aac634-e10d-49ba-b5c1-4b7793532432" alt=""><figcaption></figcaption></figure>

Vous pouvez voir une liste de tous les SU[^1]ici. Utilisez la barre de recherche en haut pour trouver un patient par son nom ou SU[^1] ID. Veuillez vous assurer de sélectionner la bonne option.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FqXqX10GKFUpZ6yfM8R8Q%2Fimage.png?alt=media&#x26;token=05d8cde9-c530-457f-91aa-86e689d6282a" alt=""><figcaption></figcaption></figure>

Dans le formulaire de l'Utilisateur du Service (SU), vous trouverez un bouton intitulé **"Nouvel ordre de réparation"**. Cliquer sur ce bouton déclenchera la création d'un ordre de réparation, permettant au système de connaître le produit à réparer.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2Fn8KPIcSCgKE30WXBNCKV%2Fimage.png?alt=media&#x26;token=eef2b8f9-96f5-4951-b9b0-baf9bb66d7b2" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Via l'application Réparation" %}
Sur la page d'accueil, allez à l'icône "Réparations".

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FQlh5Lr5TNtQF9QvOoEVa%2Fimage.png?alt=media&#x26;token=3de536ee-71ac-4d21-8c3c-6d0f0f7ee8d1" alt=""><figcaption></figcaption></figure>

Vous pouvez voir la liste des ordres de réparation existants depuis le **menu Ordres de réparation** . Pour initier un nouveau processus de réparation, cliquez simplement sur le **"Créer"** bouton.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FrRtvia0AUxOQM2AAvLH7%2Fimage.png?alt=media&#x26;token=0515fc29-dabc-4ac0-9ba2-e7f90b9a28df" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Via l'étape précédente" %}

{% endtab %}
{% endtabs %}

Si vous avez sélectionné un Utilisateur du Service où le produit à réparer n'a pas été correctement reçu, une fenêtre contextuelle apparaîtra avertissant qu'aucun article n'appartient à cet SU. Dans ce cas, revenez à l'étape précédente, «[Récupérer le produit à réparer.](recuperer-le-produit-a-reparer)»

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FP6Ct9NkD0AAIQ8B0bvmH%2Fimage.png?alt=media&#x26;token=330fb760-5d7f-4092-9f5b-f366644bd60c" alt=""><figcaption></figcaption></figure>

Sinon, après avoir sélectionné le partenaire, le système identifiera automatiquement le produit reçu pour réparation, et vous serez dirigé vers le formulaire d'ordre de réparation.

### Configuration de l'ordre de réparation

Le formulaire contient deux onglets essentiels.\
Le premier est l'onglet **"Pièces"** . Cette section répertorie tous les produits qui seront soit utilisés soit retirés d'un produit fabriqué spécifique pendant le processus de réparation.\
Ici, vous pouvez ajouter de nouvelles lignes en cliquant sur **"Ajouter une ligne"**. Lors de l'ajout d'une ligne, vous aurez la possibilité de préciser si un produit est **ajouté** (utilisé dans la réparation) ou **retiré** (enlevé de l'article d'origine).

{% hint style="danger" %}
N'incluez que les articles qui seront utilisés pendant la réparation (tels que des bandages ou des pieds de rechange). Ne sélectionnez pas l'article qui est en cours de réparation.
{% endhint %}

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FGWAc4R0xGgE9tx3lVtqp%2Fimage.png?alt=media&#x26;token=b8422cef-f356-485a-aea0-7ebf70420e77" alt=""><figcaption></figcaption></figure>

Si « Retiré » est sélectionné, vous pouvez modifier l'emplacement de destination pour soit retourner le produit en stock soit le déplacer vers l'emplacement de rebut.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FHEKbbnX3dubtCOR31BK3%2Fimage.png?alt=media&#x26;token=883663f1-9bb1-429b-af69-5901e4f2c020" alt=""><figcaption></figcaption></figure>

Le deuxième onglet est « Opérations ». Cette section inclut tous les produits de service requis pendant la réparation. Elle est principalement utilisée pour facturer des services spécifiques, tels que la main-d'œuvre ou les matériaux, au patient.

{% hint style="info" %}
Cet onglet n'est pertinent que si le centre utilise le **module de facturation** .
{% endhint %}

Une fois que tout est configuré, l'étape suivante consiste à confirmer la réparation en cliquant sur "Confirmer la réparation".

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FAJTcEAwB7LOKl0jHRtqA%2Fimage.png?alt=media&#x26;token=7347471c-ef84-4b34-9fcc-7fb1aa0f094a" alt=""><figcaption></figcaption></figure>

### 🗺️ Aperçu visuel&#x20;

{% @mermaid/diagram content="graph LR
    A[Start: From SU Form]
    A1[Start: From Repair list view]
A --> B 
A1--> B
    B[Create Repair Order]
    B --> C[Verify Selected Product]
    C --> D[Add/Remove Components for Repair]
    D --> E[Confirm the Repair]" %}

## Et ensuite ?&#x20;

Après la confirmation de l'ordre de réparation, l'étape suivante est d'initier le processus de réparation en récupérant les produits requis du stock et en les déplaçant vers l'emplacement de réparation désigné (par ex., "WH/Repair"). Cette opération est effectuée par le Responsable des stocks, qui s'assure que tous les composants nécessaires sont physiquement disponibles sur le site de réparation. Il est important de noter que le flux de réparation ne peut pas avancer tant que ce mouvement de stock n'est pas terminé, car les matériaux doivent être présents et correctement enregistrés dans le système avant que toute activité de réparation puisse commencer.



[^1]: Prestataire de services
