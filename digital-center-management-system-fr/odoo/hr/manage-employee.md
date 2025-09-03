# Gérer les employés

## Créer/Mettre à jour un employé

**Aller au module Employés**: Ouvrir le **"Employés"** application depuis le tableau de bord principal.

**Si l'employé existe déjà**: Localisez l'employé que vous souhaitez mettre à jour en utilisant la barre de recherche ou la vue en liste.\
Puis cliquez sur son profil et appuyez sur le **"Modifier"** bouton.

**Sinon, cliquez sur Créer**: Appuyez sur le **"Créer"** bouton pour ajouter un nouvel employé.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2F4GL5BRqsMZly749KfbrI%2Fimage.png?alt=media&#x26;token=c10d1c96-5c24-4c6c-b6f9-7f9bbb32f66e" alt=""><figcaption></figcaption></figure>



1. Nom de l'employé
2. Poste
3. Quelques étiquettes, vous pouvez créer des tags pour votre employé afin de pouvoir le filtrer ou le regrouper
4. Cette partie est la plus importante, cela créera l'organigramme de votre centre.

Dans les premiers onglets, vous pouvez trouver l'adresse de travail et l'emplacement, ainsi que l'organigramme basé sur le "Manager" mentionné ci‑dessus. Vous pourrez définir le validateur des demandes de congé et sélectionner la planification de l'employé. Le fuseau horaire correct sera défini par défaut

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2F296MPS9cMizR0uRi33fQ%2Fimage.png?alt=media&#x26;token=4a27ec21-1754-4dda-b71f-21e58d05c1a3" alt=""><figcaption></figcaption></figure>

Dans les seconds onglets, vous trouverez beaucoup d'informations privées de l'employé. Il est préférable de ne pas y inscrire trop de données sensibles concernant l'employé.&#x20;

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FKFE4QXnfoCCUvalmoAAH%2Fimage.png?alt=media&#x26;token=c775445d-75ee-4ab3-9972-c2e3644f85ac" alt=""><figcaption></figcaption></figure>

## Masquer les anciens employés

1. **Aller au module Employés**: Ouvrir le **"Employés"** application depuis le tableau de bord principal.
2. **Trouver l'employé**: Localisez l'employé que vous souhaitez archiver en utilisant la barre de recherche ou la vue en liste.
3. **Ouvrir le dossier de l'employé**: Cliquez sur le nom de l'employé pour accéder à son profil.
4. **Archiver l'employé**: Cliquez sur le **"Action"** bouton (coin supérieur droit), puis sélectionnez **"Archiver"** dans le menu déroulant.
5. **Confirmation**: L'employé est maintenant archivé et n'apparaîtra plus dans les listes d'employés actifs, mais ses données restent dans le système.

Pour restaurer l'employé plus tard, allez à **Filtres > Archivés**, ouvrez son profil, et cliquez sur **"Désarchiver"**.

{% @mermaid/diagram content="graph TD;
    %% HR Initiates the Employee Creation
    A["HR: Log into Odoo"] --> B["Go to Employees Module"];
    B --> C["Click on 'Create' to Add New Employee"];

    %% Employee Information Entry %%
    C --> D["Enter Employee Details (Name, Position, Department, etc.)"];
    D --> E["Assign a Work Email & Contact Details"];
    E --> F["Set Contract Type & Start Date"];
    F --> G["Upload Necessary Documents (ID, Resume, etc.)"];

    %% System Configurations
    G --> H["Assign User Access Rights"];
    H --> I["Link Employee to Payroll & Attendance"];
    I --> J["Define Work Schedule & Time Off Policies"];

    %% Final Validation & Activation
    J --> K["Review & Validate Employee Information"];
    K --> L["Save & Activate Employee Profile"];
    L --> M["Employee Successfully Created in Odoo 🎉"];
" %}

