# Comment créer un réapprovisionnement automatique

## 🧭 **Contexte**

Ce flux est utilisé pour **générer automatiquement des bons de commande** lorsque le niveau de stock d'un produit descend en dessous d'un seuil configuré. Il est couramment utilisé pour les articles consommés fréquemment, les matières premières ou les stocks essentiels qui ne doivent jamais être épuisés.

Le système vérifie **les règles de réapprovisionnement**, **les routes**, et **les informations sur le fournisseur** pour déterminer quand et comment déclencher le réapprovisionnement. Cela garantit la continuité des stocks sans suivi manuel.

## 🔄 **Flux de réapprovisionnement (étape par étape)**

### **Définir une règle de réapprovisionnement**

* Aller à **Inventaire > Produits > Règles de réapprovisionnement**.
* Choisir le produit et définir :
  * **Quantité minimale** : Lorsque le stock descend en dessous de ce niveau, Odoo réapprovisionnera.
  * **Quantité maximale** : Le système commandera suffisamment pour atteindre ce niveau.
  * **Emplacement** : Définir où la règle s'applique (par ex., WH/Stock).

### **S'assurer que les informations fournisseur sont définies**

* Ouvrir le **fichier produit** .
* Sous l'onglet **Achat** , ajoutez au moins un **Fournisseur**, avec prix et délai de livraison.
* Le fournisseur doit correspondre à l'entreprise et être marqué comme fournisseur.

### **Vérifier les routes et la méthode d'approvisionnement**

* Le produit doit avoir une **route d'achat** activée.
* La **méthode d'approvisionnement** devrait être _Lorsque le stock est nécessaire_ (comportement par défaut).

### **Déclencher le réapprovisionnement**

* Soit attendre le **job d'approvisionnement planifié** (s'exécute automatiquement selon les paramètres), ou :
* Déclencher manuellement depuis :
  * **Inventaire > Opérations > Exécuter le réapprovisionnement**
  * Ou depuis le **fichier produit** → bouton « Réapprovisionner » (déclenchement manuel)

### **Examiner le bon de commande brouillon**

* Une fois déclenché, Odoo crée une **demande de devis (brouillon)** avec des quantités suggérées.
* Vous pouvez examiner, ajuster et **confirmer** pour créer un bon de commande.

## 🗺️ Vue d'ensemble visuelle&#x20;

{% @mermaid/diagram content="graph LR
    A[Stock Drops Below Min Quantity] --> B[Reordering Rule Triggered]
    B --> C[Vendor & Route Info Checked]
    C --> D[Draft Purchase Order Created]
    D --> E[Review and Confirm PO]
    E --> F[Receipt Created and Products Delivered]
    F --> G[Stock Replenished]
" %}

## **Et ensuite**

Après confirmation du bon de commande, suivez le flux habituel : le fournisseur expédie les marchandises, vous les réceptionnez en stock, puis traitez la facture fournisseur.
