---
description: >-
  Ce chapitre traite du module de rendez-vous et de la manière d'attribuer des
  créneaux horaires aux utilisateurs des services. Il reflète le parcours
  utilisateur dans le cycle de rééducation.
---

# MODULE RENDEZ-VOUS

Configuration et prise de rendez-vous

Les Centres de Réhabilitation Physique offrent plusieurs services à l'Utilisateur du Service de Santé (USS). Ces services peuvent avoir des jours et des horaires définis où ils sont proposés. Par exemple, la pose de plâtre a lieu tous les lundis de 10h00 à 12h00. Les rendez-vous sont le moyen par lequel les prestataires gèrent leurs ressources et leur temps pour offrir des services à un USS.&#x20;

La fonctionnalité de planification des rendez-vous est destinée à donner aux utilisateurs la possibilité de planifier et de gérer les rendez-vous pour les USS dans une configuration typique de programme CICR. Grâce à cette fonctionnalité, on pourra :

1. Configurer les services pour un programme
2. Créer et gérer des rendez-vous pour un USS

La fonctionnalité de rendez-vous peut être utilisée par tout utilisateur du Programme de Réhabilitation Physique et le niveau d'accès est défini en fonction de l'ensemble de privilèges ci-dessous :

&#x20;1\. Gérer les rendez-vous de tous : Créer, modifier et supprimer les rendez-vous pour tout le monde

2\. Gérer ses propres rendez-vous : Créer, modifier et supprimer uniquement ses propres rendez-vous

3\. Gérer les services de rendez-vous : Créer, modifier et supprimer les services (Cela permet d'ajouter de nouveaux types de services ou de modifier les types de services dans les rendez-vous)

{% hint style="info" %}
Le réceptionniste dispose du droit Gérer les rendez-vous de tous - Ainsi le réceptionniste doit pouvoir planifier et modifier des rendez-vous avec tous les prestataires
{% endhint %}

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2F1qS1KNwRBH1ALnPJH5ik%2Fimage.png?alt=media&#x26;token=97bff1a4-1459-46ee-9a3e-9d7b06cf671c" alt=""><figcaption><p>Parcours utilisateur et rendez-vous </p></figcaption></figure>

### La gestion des rendez-vous

L'application de planification des rendez-vous est disponible sur la page d'accueil

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FxY0Szr8w6Sc1vNbgOjd0%2Fimage.png?alt=media&#x26;token=7dcbf458-8fdd-4400-9bf3-afc9d70f3132" alt=""><figcaption></figcaption></figure>

## Services et types de services

### À propos de la fonctionnalité <a href="#dicdlkkhsp6i" id="dicdlkkhsp6i"></a>

Un service est l'entité offerte à un USS par un prestataire. Les utilisateurs doivent sélectionner un service lors de la planification de leur rendez-vous : Pose de plâtre, Physiothérapie

### Utilisé par <a href="#uygw4343bfn5" id="uygw4343bfn5"></a>

Typiquement, la création/la mise à jour des services et des spécialités sont des activités d'administrateur. Les utilisateurs ayant le privilège « Gérer les services de rendez-vous » pourront créer un nouveau service ou modifier un service existant&#x20;

### Comment est-ce utilisé ?

Cliquez sur l'application de planification des rendez-vous sur la page d'accueil. Sous l'onglet Admin de l'application, l'utilisateur pourra définir et modifier les services. Seuls certains rôles auront accès au bouton ADMIN.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FHi8gvhACfWnNoJMPnjwl%2Fimage.png?alt=media&#x26;token=6054c918-eb55-457c-9dc6-3fb8b9f42bbf" alt=""><figcaption><p>Page d'atterrissage lors de la sélection d'un rendez-vous</p></figcaption></figure>

### &#x20;**Ajout d'un nouveau service**

* [ ] Cliquez sur le bouton "Ajouter un nouveau service" sur l'écran pour accéder à l'écran des Services

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FD7Cuw9Tk7ztgjQ0HDnRK%2Fimage.png?alt=media&#x26;token=8dcd8387-0d1a-4a14-ac70-50932c9d740b" alt=""><figcaption><p>Page d'atterrissage après avoir cliqué sur le bouton Admin</p></figcaption></figure>

L'utilisateur devra fournir les informations suivantes pour créer un nouveau service :

* [ ] **Nom du service**: Nom unique pour le service. Champ obligatoire
* [ ] **Statut initial du rendez-vous**:&#x20;

Avec deux options **Planifié, Demandé ;**

* En cas de Planifié : Un rendez-vous avec ce statut initial passe par défaut à l'état planifié
* En cas de Demandé : Un rendez-vous avec ce statut initial passe par défaut à l'état demandé et les utilisateurs ont la possibilité d'accepter ou de proposer un nouvel horaire. Une fois le nouvel horaire proposé, le rendez-vous passe par défaut à l'état planifié

- [ ] **Description :** Décrire le service

* Durée du service : Durée de la consultation requise pour offrir le service à un patient.
* Heure de début et heure de fin : Les heures de travail pour un service ou la disponibilité d'un service

{% hint style="info" %}
Exemple : Si la pose de plâtre a lieu entre 9h00 et 11h00, l'heure de début est 9h00 et l'heure de fin est 11h00 :
{% endhint %}

* [ ] **Charge maximale**: Le nombre maximal de rendez-vous pouvant être réservés pour le service pendant la disponibilité spécifiée (heures de début et de fin

{% hint style="info" %}
Par exemple, la session de pose de plâtre peut accueillir au maximum 10 USS entre 9h00 et 11h00&#x20;
{% endhint %}

* [ ] **Emplacement :** Un emplacement par défaut où un service est censé être proposé aux USS.

{% hint style="info" %}
Tous les emplacements marqués comme "emplacements de rendez-vous" dans OPENMRS seront disponibles dans le menu déroulant pour être choisis.
{% endhint %}

* [ ] **Couleur de l'étiquette :** Les services peuvent se voir attribuer des couleurs. Dans la vue calendrier, tous les rendez-vous réservés pour ce service seront affichés dans cette couleur choisie.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2Fmfz8btGjwc9d4HRVB3OR%2Fimage.png?alt=media&#x26;token=528eb486-7f99-4823-bdd5-b7c1a691af94" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
La vue calendrier affichera la couleur (ci‑dessous sont affichés des rendez-vous avec des types de service marqués par une couleur)
{% endhint %}

Pour un service avec une couleur d'étiquette, lorsqu'un rendez-vous est planifié pour ce service et consulté depuis la vue calendrier, la couleur sera affichée (ci‑dessous sont affichés des rendez-vous avec des types de service marqués par une couleur)

&#x20;![](https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FAtx2Pq4mr0zXRuG0U7dL%2Fimage.png?alt=media\&token=86f84812-bb01-4ef6-8e27-14f5f60a9f0c)

### Type de rendez-vous du service :

Les types de rendez-vous de service sont des catégories plus granulaires sous un service. Un service peut avoir différents types de rendez-vous

{% hint style="info" %}
Par exemple, évaluation initiale, consultation de suivi sous le service Pose de plâtre
{% endhint %}

* **Durée**: Chacun de ces types est associé à une durée particulière. Cela remplacera la durée du service
* T**ypes de rendez-vous de service** peuvent également être supprimés, en cliquant sur le bouton croix à côté du type de rendez-vous du service. Disponibilité du service&#x20;

1. On peut soit indiquer une disponibilité globale pour un service comme mentionné au point d ci‑dessus, soit spécifier une disponibilité plus granulaire.
2. En l'absence de disponibilité définie, par défaut le service est disponible tous les jours de la semaine et à tout moment. Plusieurs disponibilités peuvent être liées à un même service.
3. Exemple de disponibilité de service :\
   La séance de physiothérapie a lieu le lundi et le vendredi de 10h à 12h et le mercredi de 14h à 16h. Alors l'utilisateur aura 2 disponibilités définies :\
   Pour le lundi et le vendredi ; avec une heure de début et de fin de 10h à 12h\
   Pour le mercredi ; avec une heure de début et de fin de 14h à 16h
4. Charge maximale pour cette disponibilité (jour)\
   a. Le nombre maximal d'USS qui peuvent être programmés pour un service sur une durée définie dans la journée, c'est‑à‑dire la limite du nombre de rendez‑vous qui peuvent être réservés.

&#x20;     b. Cette valeur sera affichée à l'utilisateur lorsqu'il réserve un rendez‑vous pour le service.

La capture d'écran ci‑dessous montre les disponibilités du service et les types de rendez‑vous du service définis :

\
![](https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FrVzCJ7RBKS4hLexQn7R4%2Fimage.png?alt=media\&token=cb8b010d-5dae-448a-b479-3a2266238f19)

### &#x20;Création et gestion des rendez‑vous

#### Comment est‑ce utilisé ?![](file:///C:/Users/A571885/AppData/Local/Temp/msohtmlclip1/01/clip_image002.jpg)

&#x20;Cliquez sur l'application de planification des rendez‑vous sur la page d'accueil. Sous l'onglet "Gérer les rendez‑vous" de l'application, cliquez sur l'onglet Liste des rendez‑vous.

#### Créer des rendez‑vous

1. Cliquez sur "Ajouter un nouveau rendez‑vous" dans l'onglet Liste des rendez‑vous

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2Fzd2nEBJvlDxGyq0UsJ3I%2Fimage.png?alt=media&#x26;token=c5cfa19b-f989-4a8d-bb65-724ed4c209ec" alt=""><figcaption><p>Ajouter un nouveau rendez‑vous </p></figcaption></figure>



2. L'utilisateur devra remplir les détails du rendez‑vous dans le volet Ajouter un nouveau rendez‑vous

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FKv0xxSM7jDgqzgEkDqip%2Fimage.png?alt=media&#x26;token=adbd5ab9-e0fb-48d7-b66e-30bcfbe53544" alt=""><figcaption><p>Page du rendez‑vous </p></figcaption></figure>



Les informations suivantes sont requises pour créer un rendez‑vous :

{% hint style="info" %}
La sélection d'un USS, d'un service/type de service et d'une date est obligatoire pour créer un rendez‑vous.
{% endhint %}

* USS : L'USS peut être recherché par nom ou par identifiant
* Service : Le service est sélectionné dans le menu déroulant. Cela filtrera ensuite les types de rendez‑vous qui en dépendent.
* Type de rendez‑vous du service : Le type de rendez‑vous du service sera sélectionné depuis un menu déroulant.
* Rendez‑vous sans rendez‑vous préalable (Walk-in) : Les utilisateurs peuvent marquer un rendez‑vous comme un walk‑in. Par défaut, les rendez‑vous sont marqués comme Planifiés.
* Date du rendez‑vous : Elle sera choisie à partir d'un sélecteur de date. Seules les dates actuelles et futures sont autorisées.&#x20;
* Créneau horaire : Sélectionnez le créneau horaire pour un rendez‑vous.

Le menu déroulant proposera des horaires possibles en fonction de la disponibilité du service.

L'heure de fin se remplira automatiquement en fonction de la durée du service / du type de rendez‑vous du service. Par défaut 30 minutes si aucune durée n'est mentionnée.



Les utilisateurs peuvent outrepasser les heures suggérées.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2F4CCCcSYhqX0wOhXMHSUf%2Fimage.png?alt=media&#x26;token=4b738fcb-61b6-423b-b51f-3442135c1ff2" alt=""><figcaption><p>Informations indiquant que les horaires pour le rendez‑vous ne sont pas disponibles</p></figcaption></figure>

Prestataires : Sélectionnez le prestataire pour le rendez‑vous dans le menu déroulant. Seuls les prestataires dont l'attribut Fournisseur Disponible pour les rendez‑vous est défini sur true seront affichés. Ce paramètre est disponible dans OpenMRS>Administration>Prestataires>Gérer les prestataires

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FEcAsKec8ADN1n8jLWUIh%2Fimage.png?alt=media&#x26;token=0509357e-c28f-467c-9e50-c74dd75fd2ca" alt=""><figcaption></figcaption></figure>

·         Emplacement : Par défaut l'emplacement sera l'emplacement du service. L'utilisateur peut modifier l'emplacement selon le cas.

**Avertissements pour l'utilisateur**

·         Si la disponibilité du service est définie, si l'utilisateur choisit un jour ou des horaires en dehors de la disponibilité, un avertissement sera affiché à l'utilisateur.

·         Réserver un patient simultanément à des horaires qui se chevauchent avertira l'utilisateur d'un conflit.

·         Dans les deux cas mentionnés ci‑dessus, l'utilisateur peut malgré tout poursuivre et réserver un rendez‑vous en ignorant l'avertissement

&#x20;

&#x20;![](https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FPTwlTV73BBajMGMcX9nL%2Fimage.png?alt=media\&token=1ab5b8ec-c4a4-4557-afb2-c72ad344215e)

Capture d'écran ci‑dessous montrant le message d'avertissement lors de la planification d'un rendez‑vous en dehors de la plage de disponibilité.



### Gérer les rendez‑vous

#### Modifier les rendez‑vous

1. Cliquez sur le rendez‑vous que vous souhaitez modifier.
2. Cliquez sur le bouton modifier en bas

&#x20;

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FsvQYShf0hE1rJEaZgPdV%2Fimage.png?alt=media&#x26;token=ecc4d62c-dcfc-434a-8f52-de5e7a73b7d6" alt=""><figcaption><p>Vue calendrier</p></figcaption></figure>

3. En cas de rendez‑vous planifié, lorsque l'utilisateur sélectionne Modifier, le rendez‑vous s'ouvre comme indiqué ci‑dessous, où l'utilisateur a la possibilité de modifier le lieu, le prestataire et la date/heure du rendez‑vous.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2F8YZfmydQCPuyj4FDvLdg%2Fimage.png?alt=media&#x26;token=aeae0da1-fda9-45b0-8db5-2b3f41a530c7" alt=""><figcaption></figcaption></figure>

4. En cas de rendez‑vous passés ou de rendez‑vous marqués comme Manqués/Annulés/Terminés, seul le champ Notes peut être modifié.

### Accepter les rendez‑vous

En cas de statut de rendez‑vous Demandé - L'utilisateur pourra accepter le rendez‑vous et ce faisant changera le statut du rendez‑vous en accepté.

Ou l'utilisateur peut modifier le rendez‑vous et proposer un nouvel horaire et une fois fait, le rendez‑vous aura par défaut le statut accepté.

&#x20;

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FbezVVVZsR4I2RpQKgEnD%2Fimage.png?alt=media&#x26;token=3f47b75b-c675-496f-abc3-f01c94e6db5b" alt=""><figcaption></figcaption></figure>

### Statut du rendez‑vous

**Les rendez‑vous peuvent être marqués comme Enregistré, Annulé, Manqué ou Terminé.**

* Enregistrement - Marquera le statut du rendez‑vous comme Enregistré
* Terminé - Marquera le statut du rendez‑vous comme Terminé
* Annuler - Marquera le rendez‑vous comme annulé. Une fois marqué comme annulé, le rendez‑vous est supprimé du calendrier
* Manqué - Marquera le rendez‑vous comme Manqué comme indiqué ci‑dessous

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FAD1pt8307xa3e5AdUN3k%2Fimage.png?alt=media&#x26;token=e1143cbf-8f46-40d5-bdfe-0d8ef2a74000" alt=""><figcaption></figcaption></figure>





