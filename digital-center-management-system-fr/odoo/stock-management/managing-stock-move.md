# Gestion des mouvements de stock

## Qu'est-ce qu'un mouvement de stock :&#x20;

Dans Odoo, un **Mouvement de stock** représente le transfert d'un produit d'un emplacement à un autre et est essentiel pour la gestion des stocks. Il peut être déclenché par diverses opérations telles que la fabrication, les transferts internes ou les ajustements d'entrepôt. Chaque mouvement est lié à un type d'opération qui définit le processus et l'emplacement source/destination.

Un mouvement de stock passe par différents états : il commence en **Brouillon**, puis passe à **En attente de disponibilité** pendant qu'Odoo vérifie si le stock requis est présent. Une fois disponible, il devient **Prêt**, et après validation, il est marqué comme **Terminé**, mettant à jour les niveaux de stock.

Lors du traitement, les mouvements de stock peuvent nécessiter une validation, soit manuellement, soit via des règles automatisées comme FIFO ou FEFO. En fonction des paramètres de l'entrepôt, les opérations peuvent impliquer le scan de codes-barres, la préparation par lots ou des transferts en plusieurs étapes. De plus, les produits peuvent être suivis à l'aide de **Numéros de lot** ou **Numéros de série** pour assurer la traçabilité.

&#x20;Une fois terminé, le mouvement de stock met à jour le **emplacement source** en réduisant le stock et augmente le stock dans le **emplacement de destination**. Si **l'évaluation permanente des stocks** est activée, la transaction est enregistrée dans les écritures d'inventaire.



## Processus de tout mouvement de stock

Cliquez sur le bouton « Vérifier la disponibilité » pour réserver le produit, ce qui changera le statut du mouvement de stock en "Prêt".

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FbtHMsVzyEhwvQ4KaKCeu%2Fimage.png?alt=media&#x26;token=32230974-d762-4b2b-b427-6d1e3d53461a" alt=""><figcaption></figcaption></figure>

L'utilisateur peut imprimer un fichier PDF pour voir quels produits doivent être déplacés en cliquant sur le bouton d'impression et en sélectionnant « Opérations de préparation ». Si le bouton n'est pas visible, enregistrez l'enregistrement, et le bouton apparaîtra.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FXrC4ahplxOMFBNkZmsvb%2Fimage.png?alt=media&#x26;token=316998ed-b7c5-4196-9e7d-4b03364a8a7e" alt=""><figcaption></figcaption></figure>

Il existe plusieurs façons de faire avancer cette commande :

1\.     Cliquer sur "Remplir automatiquement", puis cliquer sur « Valider ».

Cela remplira automatiquement toutes les quantités disponibles dans les onglets « Opérations détaillées »

2\.     Cliquer directement sur "Valider"

Si aucune « Quantité effectuée » n'est enregistrée, une fenêtre contextuelle demandera si vous souhaitez traiter toutes les quantités réservées avant de valider. Si vous l'appliquez, cela remplira automatiquement toutes les quantités disponibles.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FzEKs332IQyA6OXPZoRQ2%2Fimage.png?alt=media&#x26;token=01121989-9776-43bf-ba64-8188bc6481f5" alt=""><figcaption></figcaption></figure>

3\.     Mettre à jour la quantité ligne par ligne.

Parfois la quantité réservée est masquée. Pour l'afficher, cliquez sur les trois points et sélectionnez "Quantité réservée". Cela affichera la quantité à récupérer et la valeur correcte à renseigner dans la colonne effectuée.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FmLJxocYZg1vyTdgBX1rR%2Fimage.png?alt=media&#x26;token=e8e0c837-ae1e-4227-9313-bf4e69fc0bf0" alt=""><figcaption></figcaption></figure>

Une fois les quantités correctement renseignées, cliquez sur "Valider". Après validation, le système demandera si vous souhaitez créer une réexpédition (backorder) pour les produits restants non encore livrés. Si vous souhaitez livrer ou récupérer ces composants plus tard, créez une réexpédition. Si vous ne voulez pas livrer les produits restants, sélectionnez « Pas de réexpédition ».

Cette étape est essentiellement la même pour chaque mouvement de stock, seul l'emplacement de stock / la destination change.

### 🗺️ Vue d'ensemble visuelle&#x20;

{% @mermaid/diagram content="flowchart TD
    A[Start - Stock Move Initiated] --> B[Create a Stock Picking]
    B --> C[Add Products and Quantities]
    C --> D[Choose Source and Destination Locations]
    D --> E[Confirm Picking]
    E --> F[Check Availability]
    F --> G{Is stock available?}
    G -- Yes --> H[Reserve Stock]
    G -- No --> I[Wait for Replenishment / Manual Reserve]
    H --> J[Validate Picking]
    J --> K[Stock Quant Updated]
    K --> L[Stock Move Completed]
    I --> G
" %}

