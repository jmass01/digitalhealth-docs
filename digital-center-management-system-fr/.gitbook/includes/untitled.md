---
title: Untitled
---

```
flowchart TD
    A([Début]) --> B[HSU nécessite un nouveau service]

    B --> C{Nouvel HSU ?}

    C -- Oui --> D[Enregistrement de l’utilisateur HSU (transversal)]
    C -- Non --> E[Recherche et confirmation du dossier HSU existant]

    D --> F[Décision initiale après enregistrement / confirmation]
    E --> F

    F --> G[Accès au menu Nouveau service]
    G --> H[Définition du plan de services de base]

    H --> I{Consentement du HSU obtenu ?}

    I -- Non --> J([Fin du service (EoS – clôturé)])
    I -- Oui --> K[Évaluation financière]

    K --> L[Évaluation finale par l’équipe interdisciplinaire (IDT)]

    L --> M{Toutes les conditions sont-elles remplies ?}

    M -- Oui --> N([Service finalisé – EoS clôturé])
    M -- Non --> O[Clôture du dossier sans prestation]

    O --> P[Processus d’abandon du formulaire]
    P --> N

```
