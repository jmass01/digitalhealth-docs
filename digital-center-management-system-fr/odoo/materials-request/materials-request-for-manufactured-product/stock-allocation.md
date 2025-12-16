# Allocation de stock

{% hint style="info" %}
### Rôles recommandés : P\&O, Responsable des stocks
{% endhint %}

## **🧭** Contexte

Ce flux se produit **après la confirmation de l'ordre de fabrication**. Le responsable des stocks est chargé de suivre ce processus pour récupérer et réserver tous les produits et composants nécessaires à l'opération de fabrication. En exécutant ces étapes dans le système, le responsable des stocks s'assure que les matériaux sont correctement alloués, préparés et validés avant le début de la production.

## 🔄 Flux étape par étape

### Accéder à la demande de matériaux

{% tabs %}
{% tab title="Via la gestion du SU" %}
Sur la page d'accueil, allez à l'icône « Gestion des utilisateurs de service ».

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FwgYqssYNXVtjPhYKKBCa%2Fimage.png?alt=media&#x26;token=e2aac634-e10d-49ba-b5c1-4b7793532432" alt=""><figcaption></figcaption></figure>

Vous pouvez voir une liste de tous les SU[^1]ici. Utilisez la barre de recherche en haut pour trouver un patient par son nom ou SU[^1] ID. Veuillez vous assurer de sélectionner la bonne option.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FqXqX10GKFUpZ6yfM8R8Q%2Fimage.png?alt=media&#x26;token=05d8cde9-c530-457f-91aa-86e689d6282a" alt=""><figcaption></figcaption></figure>

À l'intérieur du SU[^2] formulaire, vous trouverez un onglet appelé "Réceptions de stock", où sont répertoriés tous les mouvements de stock créés pour ce [SU ](#user-content-fn-2)[^2]sont listés. Dans ce cas, nous ouvrirons celui ayant le statut "En attente".

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FDKh3zt5Iv5F5M8HsKJ3H%2Fimage.png?alt=media&#x26;token=9e511615-1bc5-47b9-8763-aa18dceaaf23" alt=""><figcaption></figcaption></figure>
{% endtab %}

{% tab title="Via l" %}
Sur la page d'accueil, allez sur l'icône « Inventaire ».

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FA8eEqVYOrvo9jUwmyU30%2Fimage.png?alt=media&#x26;token=afb99b3a-628a-4ad8-8d7c-6ba1dd1c44fe" alt=""><figcaption></figcaption></figure>

Vous pouvez voir une liste de tous les types d'opérations depuis cette page. Repérez le type d'opération généralement appelé **"Préparation des composants"**. Dans cette section, vous trouverez plusieurs liens utiles : un bouton qui vous mène aux livraisons prêtes à être traitées, un nombre indiquant combien de préparations sont actuellement en attente d'un autre transfert, et un autre nombre montrant le nombre de préparations en retard.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2F79YRrbG68nVHn5gc74sd%2Fimage.png?alt=media&#x26;token=309a4468-57e2-48c6-82b0-e872add2205e" alt=""><figcaption></figcaption></figure>

Utilisez la barre de recherche en haut pour trouver la bonne préparation par leur référence, par le nom du patient, SU[^1] ID ... Veuillez vous assurer de sélectionner la bonne option.
{% endtab %}
{% endtabs %}

## Explication du formulaire de demande de matériaux

Dans ce formulaire, vous pouvez voir l'emplacement source et l'emplacement de destination en haut à gauche. La date prévue, la date limite et le document source sont affichés en haut à droite.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2F9NLIGa7zDATCCopLGqCj%2Fimage.png?alt=media&#x26;token=eb7795f5-67ff-432b-9642-69ca71514ccd" alt=""><figcaption></figcaption></figure>

S'il s'agit d'un transfert interne, vous verrez une case à cocher « Est reenfournissement » qui indique si le picking de composants est utilisé pour le reenfournissement. Cette case est purement informative et n'effectue aucune action. Pour en savoir plus sur le reenfournissement, allez à la section « Demander un reenfournissement ».

Il y a deux onglets principaux dans ce formulaire : « Opérations détaillées » et « Opérations ».

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2F0qVYiSjan3ZoeyXbIl3L%2Fimage.png?alt=media&#x26;token=d85566c1-268e-4cbd-9059-dcb5334e3629" alt=""><figcaption></figcaption></figure>

L'onglet « Opérations détaillées » montre les opérations spécifiques requises pour le mouvement de stock, y compris les quantités réservées et les numéros de lot si nécessaire.

L'onglet « Opérations » montre la quantité de produit demandée pour le mouvement. Si le mouvement est au statut brouillon, seul l'onglet « Opérations » avec la quantité de produit demandée sera visible.

## Traitement du mouvement de stock de la demande de matériaux

Cliquez sur le bouton « Vérifier la disponibilité » pour réserver le produit, ce qui changera le statut du mouvement de stock en "Prêt".

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FZk4zJJIYnCgGfCJjH6lf%2Fimage.png?alt=media&#x26;token=bc0e8bbd-a640-4202-b6ff-12830dc802a3" alt=""><figcaption></figcaption></figure>

L'utilisateur peut imprimer un fichier PDF pour voir quels produits doivent être déplacés en cliquant sur le bouton d'impression et en sélectionnant « Opérations de préparation ». Si le bouton n'est pas visible, enregistrez l'enregistrement, et le bouton apparaîtra.

![](https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FKQpWLvn8aMaJG52A8HZI%2Fimage.png?alt=media\&token=2ff50baf-d490-4d7e-88c7-3eabad0fc85b)

Il existe plusieurs façons de faire avancer cette commande :

1\. Cliquer sur "Remplir automatiquement", puis cliquer sur « Valider ».

Cela remplira automatiquement toutes les quantités disponibles dans les onglets « Opérations détaillées »

2\. Cliquer directement sur "Valider"

Si aucune « Quantité effectuée » n'est enregistrée, une fenêtre contextuelle demandera si vous souhaitez traiter toutes les quantités réservées avant de valider. Si vous l'appliquez, cela remplira automatiquement toutes les quantités disponibles.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FFHuaYgCeN9BdJPvgGhTK%2Fimage.png?alt=media&#x26;token=c93ea67a-5174-4140-a5aa-d173b1ba8bf7" alt=""><figcaption></figcaption></figure>

3\. Mettre à jour la quantité ligne par ligne.

Parfois la quantité réservée est masquée. Pour l'afficher, cliquez sur les trois points et sélectionnez "Quantité réservée". Cela affichera la quantité à récupérer et la valeur correcte à renseigner dans la colonne effectuée.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FkTA2QZKceiQC1e8TN5Kh%2Fimage.png?alt=media&#x26;token=31744236-5d87-4a69-a0a8-e3323e116daf" alt=""><figcaption></figcaption></figure>

Une fois les quantités correctement renseignées, cliquez sur "Valider". Après validation, le système demandera si vous souhaitez créer une réexpédition (backorder) pour les produits restants non encore livrés. Si vous souhaitez livrer ou récupérer ces composants plus tard, créez une réexpédition. Si vous ne voulez pas livrer les produits restants, sélectionnez « Pas de réexpédition ».

Cette étape est essentiellement la même pour chaque mouvement de stock, seul l'emplacement de stock / la destination change.

### 🗺️ Aperçu visuel

\{% @mermaid/diagram content="graph TD A\[Click 'Check Availability' button] --> B\[Stock move status changes to 'Ready'] B --> C\[Click 'Print' button and select 'Picking operations'] C --> D{Is 'Print' button visible?} D -- No --> E\[Save the record] E --> C D -- Yes --> F\[Print PDF of products to be moved]

```
F --> G[Progress Order]

subgraph Progress Options
    G --> H1[Click 'AutoFill' then 'Validate']
    G --> H2[Click 'Validate' directly]
    G --> H3[Update quantities line by line]
end

H2 --> I{Are 'Done quantities' recorded?}
I -- No --> J[Popup: Process all reserved quantities?]
J -- Yes --> H1
J -- No --> K[Validate as is]

H3 --> L[Click three dots > Select 'Reserved quantity' to show reserved qty]

H1 & K & L --> M[Quantities populated correctly]

M --> N[Click 'Validate']

N --> O{Create backorder for remaining products?}
O -- Yes --> P[Create backorder for later delivery]
O -- No --> Q[Select 'No backorder' to skip remaining delivery]

P & Q --> R[Process complete]
```

" %\}

## Et ensuite ?

Après avoir réservé et validé les composants, l'étape suivante consiste à procéder au traitement de l'Ordre de travail au sein de l'Ordre de fabrication (MRP). Selon le résultat, il peut également y avoir une demande optionnelle de composants supplémentaires, par exemple pour le reenfournissement, si nécessaire.

[^1]: Fournisseur de service

[^2]: utilisateur de service
