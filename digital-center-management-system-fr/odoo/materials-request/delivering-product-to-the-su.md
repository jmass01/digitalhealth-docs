# Remise du produit à l'Utilisateur de Service

{% hint style="info" %}
## Rôles recommandés : P\&O
{% endhint %}

## **🧭** Contexte&#x20;

Ce flux doit être suivi **après que l'Ordre de Fabrication a été validé** ou **lorsqu'une livraison a été créée manuellement pour un Utilisateur de Service (SU)**. À ce stade, le produit est prêt à être expédié et le processus de livraison doit être complété pour garantir que le produit parvienne au SU et que le stock soit mis à jour avec précision.

## 🔄 Flux étape par étape&#x20;

### Accéder à l'ordre de transfert

{% tabs %}
{% tab title="Via la gestion du SU" %}
Sur la page d'accueil, allez à l'icône « Gestion des utilisateurs de service ».&#x20;

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FwgYqssYNXVtjPhYKKBCa%2Fimage.png?alt=media&#x26;token=e2aac634-e10d-49ba-b5c1-4b7793532432" alt=""><figcaption></figcaption></figure>

Vous pouvez voir une liste de tous les SU[^1]ici. Utilisez la barre de recherche en haut pour trouver un patient par son nom ou SU[^1] ID. Veuillez vous assurer de sélectionner la bonne option.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FqXqX10GKFUpZ6yfM8R8Q%2Fimage.png?alt=media&#x26;token=05d8cde9-c530-457f-91aa-86e689d6282a" alt=""><figcaption></figcaption></figure>

Dans le formulaire SU, vous trouverez un onglet intitulé "**Éléments de stock**". En cliquant dessus, vous verrez tous les ordres de transfert associés à cet Utilisateur de Service spécifique.&#x20;

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FniSbVG2ONAzGYSPJCWr5%2Fimage.png?alt=media&#x26;token=49962a84-dcab-4a48-a697-771b9a223e49" alt=""><figcaption></figcaption></figure>


{% endtab %}

{% tab title="Via l'application Inventaire" %}
Sur la page d'accueil, allez sur l'icône « Inventaire ».&#x20;

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FeNwL1w4TBoeI2GvrH9hi%2Fimage.png?alt=media&#x26;token=7ae73df6-66b3-4ebe-9716-8f103b064905" alt=""><figcaption></figcaption></figure>

Vous pouvez consulter la liste de tous les types d'opération depuis cette page. Repérez le type d'opération appelé **"Ordres de livraison"**. Dans cette section, vous trouverez plusieurs liens utiles : un bouton qui vous mène aux livraisons prêtes à être traitées, un chiffre indiquant combien de livraisons attendent actuellement un autre transfert, et un autre chiffre montrant le nombre de livraisons en retard.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FpZtgdjXkTQeuvC5jAe0S%2Fimage.png?alt=media&#x26;token=069aa569-8132-4379-b4a8-d5165dea9d7a" alt=""><figcaption></figcaption></figure>

Utilisez la barre de recherche en haut pour trouver la bonne livraison par sa référence, par le nom du patient, SU[^1] ID ... Veuillez vous assurer de sélectionner la bonne option.
{% endtab %}
{% endtabs %}

### Validation de l'ordre de transfert

Dans les deux cas, le processus suit les mêmes étapes que pour tout autre mouvement de stock. Pour savoir comment le traiter, référez-vous à «[Gérer un mouvement de stock](../gestion-des-stocks)».

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FwL7HOsCE6UGcr9GxZXeL%2Fimage.png?alt=media&#x26;token=b3270733-000f-456a-ac88-09f093d46e19" alt=""><figcaption></figcaption></figure>

&#x20;La validation de cet ordre signifie que le produit a été reçu par le client et ne sera plus disponible en stock. Cette action met à jour l'inventaire en conséquence, reflétant l'expédition sortante et garantissant une gestion précise des stocks. Cela marque également la fin du processus.



### 🗺️ Aperçu visuel&#x20;

{% @mermaid/diagram content="graph LR
    B[Delivery Order Created]
    B --> C[Check Product Availability]
    C --> D{Are Products Available?}
    D -- Yes --> R1[Autofill]
    R1 --> L{Is the correct Lot number selected?}
    L -- Yes --> E[Validate Delivery Order]
    E --> G[Delivery Completed]
    L -- No --> F[Correct the Lot number]
    F --> R1

    D -- No --> H[Wait for internal transfer / Restock]
    H --> C" %}

## Et ensuite ?&#x20;

En validant cet ordre, vous **confirmez que le produit** a été livré avec succès à l'Utilisateur de Service et n'est plus en stock. L'inventaire est automatiquement mis à jour pour refléter ce changement. Une fois cette étape finale effectuée, le processus est terminé. Aucune autre action n'est requise.

[^1]: Fournisseur de service
