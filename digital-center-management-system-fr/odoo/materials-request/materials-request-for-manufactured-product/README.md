# Demande de matériel pour produit fabriqué

Cette section décrit le **processus MRP (planification des ressources de fabrication)** dans Odoo, pour la gestion des demandes d’usagers de service concernant des dispositifs médicaux (prothèses, orthèses, béquilles, fauteuils roulants, aides à la marche, etc.).

## Prérequis

Le processus commence lorsqu’un usager de service demande un dispositif spécifique. Cela déclenche une série d’étapes pour s’assurer que l’article demandé est correctement configuré, fabriqué et livré.

## Flux du processus MRP

{% stepper %}
{% step %}
#### Identifier l’usager de service

Localisez l'utilisateur de service dans le menu « Gestion des l'utilisateurs de service ».
{% endstep %}

{% step %}
#### [Créer la nomenclature (BoM)](demande-de-materiaux-pour-produit-manufacture/creation-de-la-configuration-de-nomenclature-bom/)

Créez une configuration de nomenclature pour définir les attributs du produit (par exemple : côté, taille, couleur).
{% endstep %}

{% step %}
#### [Valider la nomenclature (BoM)](demande-de-materiaux-pour-produit-manufacture/gestion-des-ordres-mrp/)

Confirmez la configuration. Dans certains cas, la validation d’un supérieur est requise pour poursuivre l’ordre de fabrication.
{% endstep %}

{% step %}
#### Processus de fabrication

* Démarrez l’ordre de fabrication.
* Traiter les ordres de travail étape par étape.
* Certaines étapes peuvent nécessiter une validation supplémentaire par un autre utilisateur.
{% endstep %}

{% step %}
#### Finaliser l’ordre de fabrication

Complétez le processus de fabrication une fois que tous les ordres de travail sont complétés.
{% endstep %}

{% step %}
#### Remettre le dispositif à l’usager de service

* Accédez au **formulaire de l’usager de service**.
* Vérifiez s’il existe une livraison ouverte et complétez le processus de livraison.
{% endstep %}
{% endstepper %}

## Organigramme

```mermaid
flowchart TD
    subgraph user1["P&O"]
        A["Identifier l'usager de service"] --> B["Localiser l’US dans 'Gestion des usagers de service'"]
        B --> C["Configurer la nomenclature (BoM)"]
        C --> D["Définir les attributs : côté, taille, couleur"]
        D --> E["Valider la BoM"]
        E --> n1["Validation par un supérieur nécessaire ?"]
    end

    subgraph user2["Responsable P&O"]
        F["Valider l’ordre de fabrication"]
    end

    subgraph user3["P&O"]
        n2["Valider l’ordre de fabrication"]
    end

    subgraph Benchworker["Atelier"]
        G2["Récupérer les composants en stock"]
        H["Démarrer le processus de fabrication"]
        I["Traiter les ordres de travail étape par étape"]
        K["Finaliser la fabrication"]
    end

    n1 -- Oui --> user2
    n1 -- Non --> user3
    F --> G2
    G2 --> H
    H --> I
    I --> K
    K --> L["Remettre le dispositif à l’usager"]
    L --> M["Accéder au formulaire de l'usager"]
    M --> N["Vérifier la livraison ouverte"]
    N --> O["Compléter la livraison"]

```
