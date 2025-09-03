# FAQ

### **Le DCMS**&#x20;

#### **Question :** Qu'est-ce que le DCMS ?

Le Centre Numériquee[^1] Le Système de Gestion des Centres Numériques (DCMS) est une solution innovante développée pour le Programme de Réadaptation Physique dans le cadre du Programme d'Investissement à Impact Humanitaire (PHII). Il fonctionne en collaboration avec Pearl pour améliorer l'efficacité et l'autonomie des Centres de Réadaptation. Le système comprend deux outils numériques : un système de Dossier Médical Électronique (DME) nommé « OpenMrs » et un système de Planification des Ressources d'Entreprise (ERP) appelé « Odoo ». Ces outils visent à améliorer la qualité des services et la gestion globale des centres. Le DME fournit un module de rendez‑vous pour les utilisateurs des services de santé et les utilisateurs du DCMS, tandis que la nouvelle application « SuperSet » optimise la collecte de données.

#### Question : Qu'est‑ce que SuperSet ?

Apache Superset est un outil open source de visualisation et d'exploration de données. Il offre une interface intuitive pour se connecter à divers jeux de données et les combiner en une seule visualisation ou un tableau de bord. Superset inclut une large gamme de visualisations préinstallées, en faisant une solution puissante et simple pour l'analyse des données.

### **La mise à jour du Système de Gestion des Patients**

#### Question : Qu'est‑ce que le SGP ?

Le Programme de Réadaptation Physique du CICR a développé le Système de Gestion des Patients (SGP) il y a 25 ans comme outil de reporting. Il sera bientôt mis hors service en raison de son obsolescence

#### Question : Quelle est la différence dans le DCMS ?

Le Système de Gestion des Centres Numériques (DCMS) est un outil gratuit créé avec la contribution des équipes du CICR, permettant aux Centres d'en bénéficier même après la fin du soutien du CICR. Il est conçu pour améliorer l'efficacité et soutenir le reporting des données dans les Centres de Réadaptation Physique.

#### Question : Les informations contenues dans le SGP peuvent‑elles être migrées vers le DCMS ?

Lors du déploiement du DCMS, les données du SGP seront migrées vers le DCMS, qui est pris en charge uniquement par PMS5. Les centres utilisant des versions antérieures doivent d'abord passer à PMS4, puis à PMS5, avant de migrer.&#x20;

#### Question : Le DCMS remplacera‑t‑il le SGP dans tous les Centres PRP soutenus par le CICR ?

Le SGP sera mis hors service car il est obsolète ; il n'est plus supporté et est dépassé, reposant uniquement sur Internet Explorer, que Microsoft désactivera bientôt. Les Centres de Réadaptation Physique ne sont pas obligés de changer immédiatement, mais le DCMS mettra progressivement en place un nouveau système pour remplacer le SGP là où il sera applicable.

### Modèle de soutien et durabilité&#x20;

#### Question : Quel est le modèle de soutien pour les utilisateurs externes ?

Le CICR, avec l'assistance du DCMS, a développé un modèle de support pour les partenaires externes. Ils peuvent accéder à ce support via un e‑mail dédié : servicedesk@icrc.org. En interne, le CICR utilisera l'application ServiceNow pour le support

#### Question : Comment puis‑je contacter le support ?

Un courriel doit être envoyé à servicedesk@icrc.org avec pour sujet : « \[DCMS / Lieu] + problème ». Le problème doit être expliqué plus en détail dans le corps du message.

### DONNÉES/SGP/RAPPORT/SUPERSET

#### Question : Lorsque les données du SGP sont migrées vers le DCMS, le DME reconnaîtra‑t‑il le dossier et les données HSU ?

Chaque dossier HSU enregistré dans le SGP migrera l'historique, avec le numéro SGP, le numéro d'identité HSU et le dernier épisode de services. Il peut arriver que certaines informations manquent ; il est important de mettre à jour ces informations avec l'HSU.

#### Question : Que se passe‑t‑il avec le flux de travail lorsque le SGP est migré ?

L'épisode de service est clôturé. Vous devez démarrer un nouveau service ou un suivi selon l'état de l'utilisateur du service de santé. Un épisode de service correspond à un cycle de réadaptation, qu'il s'agisse d'un nouveau service ou d'un suivi.

#### Question : Le DCMS et le MAD sont‑ils connectés, ou les informations doivent‑elles être dupliquées ?

Réponse : DHIS2 (District Health Information System 2) est un outil open source. Le rapport DCMS (format excel) et le superset rapporteront les données pertinentes pour DHIS2, mais il n'y a pas encore de synchronisation vers la plateforme DHIS2.

#### Question : certains HSU ne sont pas vus lors de la clinique interdisciplinaire car ils viennent pour un petit service comme un dispositif préfabriqué, comment aurai‑je le dossier de ces utilisateurs ?

Pour un service efficace et une visibilité de l'activité, chaque HSU devrait être enregistré dans le DCMS et suivre le flux de travail même s'il s'agit d'un service mineur.

#### Question : l'équipe de physiothérapie a oublié d'enregistrer les séances de kinésithérapie pour un HSU qui a été sorti, pouvons‑nous entrer des données rétroactivement et si oui comment le faire ?

Oui, il est possible d'entrer les données (séance de kinésithérapie) pour une visite passée : il faut entrer dans la visite passée pertinente, sélectionner l'enregistrement de la séance de kinésithérapie et saisir les informations autant que nécessaire.

### Évaluation HSU et flux de travail

#### Question : Dans le formulaire d'évaluation initiale, où puis‑je trouver la condition Malformation congénitale ou Disparité de membre inférieur ?

La liste des conditions est basée sur la logique de la CIM‑10 de l'OMS ; par exemple, vous pouvez aller dans le menu déroulant des conditions présentes et sélectionner « Malformations et déformations congénitales du système musculo‑squelettique (Q65‑Q79) » où vous pouvez trouver « Défauts de réduction du membre inférieur » ou dans le menu déroulant des conditions « Autres troubles articulaires (M20‑M25) » et vous pouvez sélectionner « déformation acquise du membre, non spécifiée ».

#### Question : pouvons‑nous compléter la fiche technique pour un cas bilatéral dans le même formulaire ?

Pour chaque fiche technique nous avons l'option gauche ou droite ; chaque moignon doit être complété sur une fiche afin d'éviter toute confusion dans la mesure.

#### Question : un HSU ayant reçu des services d'autres PRC dans le même pays pourrait‑il avoir le même numéro d'identification dans OpenMrs ?

Si les Centres ne sont pas synchronisés entre eux, l'identifiant HSU ne sera pas mis à jour dans OpenMrs d'un autre centre car les données HSU doivent être créées.

#### Question : Comment gérer un HSU qui vient pour un nouveau service et une réparation lors de la même visite ?

Les deux flux de travail sont exclusifs et doivent être saisis séparément ; vous pouvez commencer par le flux de travail de réparation et après la clôture du service vous ouvrez un nouveau service.

#### Question : Dois‑je créer un HSU dans Odoo s'il est créé dans OpenMRS ?

Non, il y a une synchronisation entre les deux applications, l'HSU est automatiquement mis à jour dans Odoo.

#### Question : Comment fusionner un HSU qui a été créé deux fois dans OpenMrs ?

Sur la page d'accueil du DCMS, vous pouvez sélectionner le widget gestion des données et l'option fusionner patient/HSU.

![](https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2F7fS3Yy3ryzqQvavYnAwE%2Fimage.png?alt=media\&token=91c60dfe-4d1f-4125-a213-a8e15a2aa520) ![](https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FaMpElHGDUslsn5bEHPFQ%2Fimage.png?alt=media\&token=f40ed272-70c5-4fea-a0fe-d766792ba9bd)

&#x20; Question : Comment les conditions médicales sont‑elles cartographiées dans Openmrs ?

Via les dossiers médicaux électroniques (DME) pour les utilisateurs des services de santé qui peuvent créer et gérer les dossiers médicaux. La cartographie des conditions est basée sur la Classification Internationale des Maladies 10 de l'Organisation mondiale de la santé (OMS).

La CIM‑10 est disponible dans les formulaires « Évaluation initiale » et « Suivi d'évaluation du service » où toutes les conditions sont basées sur le profil des HSU venant aux Centres de Réadaptation Physique. Les options du menu déroulant CIM‑10 sont également basées sur les données DHIS2.

### Module de rendez‑vous et tableaux de bord des professionnels&#x20;

#### Question : Puis‑je voir tous les rendez‑vous créés et attribués à un quelconque HSU ?

Oui, le module de rendez‑vous est ouvert et visible pour chaque utilisateur du DCMS. Il offre transparence et flexibilité à chaque utilisateur pour éviter les « conflits » de rendez‑vous.

#### Question : Puis‑je refuser ou modifier un rendez‑vous

&#x20;_Pour modifier un rendez‑vous :_

o   Cliquez sur le rendez‑vous que vous voulez modifier.

o   Cliquez sur le bouton modifier.

o   Remplissez les détails du rendez‑vous dans le volet Ajouter un nouveau rendez‑vous.

o   Les détails requis incluent la sélection d'un Patient, du Service/type de service et de la Date.

o   Ajustez la Date du rendez‑vous, le créneau horaire, les prestataires et le lieu selon les besoins.

o   Enregistrez les modifications.

_Pour accepter un rendez‑vous :_

o   Si le statut du rendez‑vous est « Demandé », vous pouvez accepter le rendez‑vous, ce qui changera le statut en « Accepté ».

o   Alternativement, vous pouvez modifier le rendez‑vous et proposer une nouvelle heure ; une fois fait, le rendez‑vous aura par défaut le statut « Accepté ».

Remarque : Lors de la modification d'un rendez‑vous, si la disponibilité du service est définie et que vous choisissez un jour ou un horaire en dehors de cette disponibilité, un avertissement apparaîtra.

· &#x20;



Document(s) source : [https://collab.ext.icrc.org/sites/TS\_ASSIST/activities/HEALTH/DigitalHealth/Health%20Solutions%20User%20Guides/DCMS/REFERENCE\_GUIDE\_OPENMRS\_censored.pdf](https://collab.ext.icrc.org/sites/TS_ASSIST/activities/HEALTH/DigitalHealth/Health%20Solutions%20User%20Guides/DCMS/REFERENCE_GUIDE_OPENMRS_censored.pdf)

[^1]: 
