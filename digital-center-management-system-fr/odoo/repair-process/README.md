# Processus de réparation



🔄 Aperçu du flux de réparation

Ce flux décrit le **processus de réparation complet**, commençant par la réception de l'article de l'Utilisateur du Service (SU) jusqu'à la livraison finale du produit réparé. Il inclut l'interaction entre le technicien et le **Gestionnaire de stock**, qui joue un rôle crucial dans la gestion de la disponibilité des stocks et la préparation des produits.

1. **Réception et lancement de la réparation**\
   Le processus commence lorsque l'Utilisateur du Service retourne l'article pour réparation. Le technicien sélectionne le produit correct et le numéro de lot associé, puis valide le prélèvement pour confirmer la réception. Un **Bon de réparation** est ensuite créé.
2. **Configuration du bon de réparation**\
   Dans le formulaire de réparation, le technicien sélectionne le produit à réparer et valide la configuration de la réparation.
3. **Vérification et préparation du stock**\
   Le système vérifie si les pièces ou matériaux nécessaires à la réparation sont disponibles en stock :
   * **Si non disponible**, un prélèvement de stock est créé et envoyé au **Gestionnaire de stock**, qui prépare les articles nécessaires.
   * Le gestionnaire de stock récupère le produit correct du stock, le prépare et le remet au **opérateur d'atelier**.
4. **Exécution de la réparation**\
   Une fois les articles nécessaires disponibles, le technicien commence et effectue la réparation.
5. **Livraison du produit réparé**\
   Après la réparation, une livraison est créée pour retourner l'article réparé à l'Utilisateur du Service. Une fois validée, la livraison est clôturée et le produit est officiellement rendu au SU.

Ce flux garantit **la traçabilité des pièces**, **des mouvements de stock précis**, et une **séparation claire des rôles** entre la gestion des stocks et l'exécution des réparations.

### 🗺️ Aperçu visuel  <a href="#visual-overview" id="visual-overview"></a>

{% @mermaid/diagram content="flowchart TD
 subgraph askProduct["Stock Keeper"]
        G0["Receive stock picking"]
        G2["Prepare Product"]
        G1["Get Correct Product from Stock"]
        G3["Deliver to Benchworker"]
  end
    A["Receive Item from Service User"] --> B["Select Correct Product & Lot Number"]
    B --> C["Validate the Picking"]
    C --> D["Create a Repair Order"]
    D --> E["Select Product for Repair"]
    E --> F["Validate the Repair"]
    F --> n1["Is Stock Available?"]
    G1 --> G2
    G2 --> G3
    G["Retrieve stock from the store keeper"] --> H["Start the Repair"]
    H --> I["End the Repair"]
    I --> J["Create Delivery to Service User"]
    J --> K["Close the Delivery"]
    n1 -- No --> G0
    n1 -- Yes --> H
    G3 --> G
    G0 --> G1

    n1@{ shape: diam}

" %}

