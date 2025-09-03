# Demande de matériaux pour produit manufacturé

Dans cette section, nous expliquerons le déroulement du processus de planification des ressources de fabrication (MRP) dans Odoo, spécifiquement pour la gestion des demandes des usagers de service concernant des dispositifs médicaux tels que prothèses, orthèses, béquilles, fauteuils roulants, aides à la marche ou autres matériels.

## Prérequis

Le processus commence lorsqu’un usager de service demande un dispositif spécifique. Cela déclenche une série d’étapes pour s’assurer que l’article demandé est correctement configuré, fabriqué et livré.

## Flux du processus MRP

{% stepper %}
{% step %}
### Identifier l’usager de service

Localisez l’usager de service dans le menu « Gestion des usagers de service ».
{% endstep %}

{% step %}
### [Créer la nomenclature (BoM)](demande-de-materiaux-pour-produit-manufacture/creation-de-la-configuration-de-nomenclature-bom)

Créez une configuration de nomenclature pour définir les attributs du produit (par exemple : côté, taille, couleur).
{% endstep %}

{% step %}
### [Valider la nomenclature (BoM)](demande-de-materiaux-pour-produit-manufacture/gestion-des-ordres-mrp)

Confirmez la configuration. Dans certains cas, la validation d’un supérieur est requise pour poursuivre l’ordre de fabrication.
{% endstep %}

{% step %}
### Processus de fabrication

* Démarrez l’ordre de fabrication.
* Traitez chaque ordre de travail étape par étape.
* Dans certains cas, une validation supplémentaire par une autre personne peut être requise.
{% endstep %}

{% step %}
### Terminer l’ordre de fabrication

Finalisez le processus de fabrication une fois que tous les ordres de travail sont complétés.
{% endstep %}

{% step %}
### Remettre le dispositif à l’usager de service

* Accédez au formulaire de l’usager de service.
* Vérifiez s’il existe une livraison ouverte et complétez le processus de livraison.
{% endstep %}
{% endstepper %}

## Organigramme

{% @mermaid/diagram content="---
config:
  theme: mc
---
flowchart TD
 subgraph user1["P&O"]
        B@{ label: "Locate SU in 'Service User Management' Menu" }
        A["Identify the Service User"]
        C["Configure the Bill of Materials (BoM)"]
        D["Create BoM Configuration (Side, Size, Color)"]
        E["Validate the Bill of Materials (BoM)"]
  end
 subgraph user2["Head of P&O"]
        F["Validate the Manufacturing order"]
  end
 subgraph user3["P&O"]
        n2["Validate the Manufacturing order"]
  end
 subgraph Bencworker["Benchworker"]
        G2["Retrieve the Components from the stock"]
        H["Start Manufacturing Process"]
        I["Process Work Orders Step-by-Step"]
        K["Finalize Manufacturing Process"]
  end
    A --> B
    B --> C
    C --> D
    D --> E
    user1 --> n1(["Need a Superior Validation"])
    n1 -- Yes --> user2
    n1 -- No --> user3
    F --> G["Stock picking created"]
    G --> G2
    G2 --> H
    H --> I
    K --> L["Deliver the Device to SU"]
    L --> M["Go to Service User Form"]
    M --> N["Check for Open Delivery"]
    N --> O["Complete the Delivery Process"]
    user3 --> G
    I --> K
    B@{ shape: rect}
" %}

