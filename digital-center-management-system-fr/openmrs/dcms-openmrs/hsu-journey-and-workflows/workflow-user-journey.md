---
description: Nouveau service et suivi/réparation (flux de travail en détail)
---

# Parcours utilisateur du flux de travail

Enregistrer le HSU ou trouver le dossier HSU arrivant au PRC

### a. Flux de travail nouveau service&#x20;

{% stepper %}
{% step %}
### Commencer la visite

<mark style="color:vert;">Décision initiale après l'enregistrement</mark> et décision d'envoyer pour un nouveau service (enregistrer et valider)
{% endstep %}

{% step %}
### Évaluation initiale (équipe interdisciplinaire)

* <mark style="color:vert;">Résultat initial et définition des objectifs (évaluations optionnelles)</mark>
* <mark style="color:vert;">Plan de service de base + consentement clinique (planifier le service)</mark>
{% endstep %}

{% step %}
### Évaluation de la capacité financière

<mark style="color:vert;">(si non approuvé) Évaluation socio-économique + décision de financement</mark>
{% endstep %}

{% step %}
### Services&#x20;

Fiches techniques

Évaluation en physiothérapie

Évaluation du fauteuil roulant

Aides à la marche

Pied bot

Paralysie cérébrale
{% endstep %}

{% step %}
### Évaluation finale Résultat et définition des objectifs (Clôture automatique du service)

Rendez-vous pour visite de suivi
{% endstep %}
{% endstepper %}

{% @mermaid/diagram content="
  flowchart TB
    %% Main workflow
    A["Register the HSU or find the HSU file coming to the PRC"] --> 
    B["Start the visit"] --> 
    C["Initial decision after registration and decision to send for new service (save and validate)"] --> 
    D["Initial Assessment (interdisciplinary team)"]

    %% Optional assessment
    D -.-> D2["Optional Assessment"]

    D --> E["Initial outcome and goal setting + Basic service plan + clinical consent"]
    E --> E1["Plan Service"]
    E1 --> F["Financial capacity assessment + socio-economic assessment"]
    E2 --> F["Financing decision if financial capacity is not approved"]
    F --> G["Any Services"]

    %% Subgraph for services (no label), all connect directly to Final Assessment
    subgraph "" direction LR
        G --> G1["Technical cards"]
        G --> G2["Physiotherapy assessment"]
        G --> G3["Wheelchair assessment"]
        G --> G4["Walking Aids"]
        G --> G5["Club foot"]
        G --> G6["Cerebral palsy"]
    
    G1 --> K
    G2 --> K
    G3 --> K
    G4 --> K
    G5 --> K
    G6 --> K

    %% Final steps
    K["Final assessment Outcome and goal setting + Automatic closure of service"]
    K --> L["Appointment for follow-up visit"]

    %% Styling
    classDef default fill:#f0f0f0,stroke:#333,stroke-width:1.5px;
    classDef optional stroke-dasharray: 5 5,stroke:#888,fill:#ffffff;
    class D2 optional;" %}

### b. Flux de travail nouveau service avec évaluation intermédiaire&#x20;

**Dans le cas où vous devez ajuster le service ;**

* Pour ajouter un produit ou un service supplémentaire (comme des séances de physiothérapie supplémentaires)
* Pour évaluer les progrès et les objectifs du traitement ; vous pouvez suivre l'étape suivante.&#x20;

{% stepper %}
{% step %}
### Service&#x20;

Physiothérapie, Fiche technique, Fauteuil roulant, Pied bot, Paralysie cérébrale, Aides à la marche
{% endstep %}

{% step %}
### Évaluation intermédiaire Résultat et définition des objectifs

Décision : Ajuster le service si nécessaire&#x20;
{% endstep %}

{% step %}
### Plan de service de base

Ajouter le(s) service(s)
{% endstep %}

{% step %}
### Évaluation de la capacité financière&#x20;

si non approuvé :

* Sélectionnez effectuer **socioéconomique** et compléter **Décision de financement**
* Sélectionner **Socioéconomique** déjà enregistré, si vous sélectionnez cette option vous pouvez déjà aller à **Décision de finan**cement.
{% endstep %}

{% step %}
### Service(s)
{% endstep %}

{% step %}
### Évaluation finale Résultat et définition des objectifs (Clôture automatique du service)

Rendez-vous pour visite de suivi
{% endstep %}
{% endstepper %}

{% @mermaid/diagram content="flowchart TB
    %% Main workflow
    A["Register the HSU or find the HSU file coming to the PRC"] --> 
    B["Start the visit"] --> 
    C["Initial decision after registration and decision to send for new service (save and validate)"] --> 
    D["Initial Assessment (interdisciplinary team)"]

    %% Optional assessment
    D -.-> D2["Optional Assessment"]

    D --> E["Initial outcome and goal setting + Basic service plan + clinical consent"]
    E --> E1["Plan Service"]
    E1 --> F["Financial capacity assessment + socio-economic assessment (completed with financing decision if financial capacity is not approved)"]
    F --> G["Any Services"]

    %% Subgraph for services
    subgraph "" direction LR
        G --> G1["Technical cards"]
        G --> G2["Physiotherapy assessment"]
        G --> G3["Wheelchair assessment"]
        G --> G4["Walking Aids"]
        G --> G5["Club foot"]
        G --> G6["Cerebral palsy"]
        %% Intermediate Assessment after subgraph
    G1 --> H["Intermediate Assessment and Goal Setting "]
    G2 --> H
    G3 --> H
    G4 --> H
    G5 --> H
    G6 --> H

    %% Decision paths
    H -- Yes --> I["Adjust service + new plan + financial review"]
    H -- No --> K["Final assessment Outcome and goal setting + Automatic closure of service"]

    I --> J["Additional Services"]
    J --> K
    K --> L["Appointment for follow-up visit"]

    %% Styling
    classDef default fill:#f0f0f0,stroke:#333,stroke-width:1.5px;
    classDef optional stroke-dasharray: 5 5,stroke:#888,fill:#ffffff;
    class D2 optional;
" %}



### C. Flux de travail Réparation ou Suivi

{% stepper %}
{% step %}
### Enregistrer le HSU ou trouver le dossier HSU arrivant au PRC&#x20;


{% endstep %}

{% step %}
### Commencer la visite (Ouvrir l'épisode de service)

Décision initiale après l'enregistrement et décision d'envoyer en suivi (enregistrer et validé)
{% endstep %}

{% step %}
### Évaluation de suivi du service&#x20;

Décision : Suivi/réparation ou nouvelle évaluation interdisciplinaire ou terminer le suivi
{% endstep %}

{% step %}
### Évaluation de la capacité financière

Si non approuvé, compléter le socio-économique déjà enregistré&#x20;

* décision&#x20;
{% endstep %}

{% step %}
### Plan de suivi du service (Clôture automatique de l'épisode de service)

Si la réparation d'AT est oui, sélectionnez les options pertinentes de catégorie de service avec l'ajustement et/ou la réparation en tant que service.
{% endstep %}
{% endstepper %}







{% @mermaid/diagram content="flowchart TB
    %% Main flow
    A["Register the HSU or find the HSU file coming to the PRC"] --> 
    B["Start the visit (Open the Episode of service)"] --> 
    C["Initial decision after registration and decision to send for follow-up (save and validated)"] --> 
    D["Service Follow-up Assessment"] --> 
    E["Decision: Follow-up/Repair OR New Interdisciplinary Assessment OR End the follow-up"]

    %% Follow-up path
    E --> F["Financial capacity assessment"]
    F --> G["If not approved: complete the socioeconomic already recorded"]
    G --> H["Financing Decision"]

    H --> I["Service Follow-up Plan<br><br>If AT repair = yes → select relevant service category with Adjustment or/and Repair as service<br><br>(Automatic closure of Episode of service)"]

    I --> J["Appointment for follow-up or new service"]

    %% Styling
    classDef default fill:#f0f0f0,stroke:#333,stroke-width:1.5px;
" %}



### D. Flux de travail Suivi/réparation vers Nouveau Service&#x20;
