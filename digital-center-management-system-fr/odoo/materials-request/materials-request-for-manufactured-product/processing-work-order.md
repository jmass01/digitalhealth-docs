# Traitement de l'ordre de travail

{% hint style="info" %}
## Rôles recommandés : P\&o, Benchworker
{% endhint %}

## **🧭** Contexte&#x20;

Cette étape a lieu **après que l'ordre de fabrication a été créé** et **les composants requis ont été reçus à l'emplacement de l'atelier**. À ce stade, l'ordre de travail est prêt à être traité, et le système peut exiger une validation avant que l'exécution puisse commencer — en fonction de la configuration de votre installation.

## 🔄 Flux étape par étape&#x20;

### Accéder à l'ordre de fabrication

{% tabs %}
{% tab title="Via la gestion du SU" %}
Sur la page d'accueil, allez à l'icône « Gestion des utilisateurs de service ».&#x20;

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FwgYqssYNXVtjPhYKKBCa%2Fimage.png?alt=media&#x26;token=e2aac634-e10d-49ba-b5c1-4b7793532432" alt=""><figcaption></figcaption></figure>

Vous pouvez voir une liste de tous les SU[^1]ici. Utilisez la barre de recherche en haut pour trouver un patient par son nom ou SU[^1] ID. Veuillez vous assurer de sélectionner la bonne option.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FqXqX10GKFUpZ6yfM8R8Q%2Fimage.png?alt=media&#x26;token=05d8cde9-c530-457f-91aa-86e689d6282a" alt=""><figcaption></figcaption></figure>

Dans le formulaire SU, vous trouverez deux boutons : "[**GPAO**](#user-content-fn-2)[^2] **Production**" et "[**GPAO**](#user-content-fn-2)[^2] **Ordre de travail**". Le premier ouvre l'ordre de production complet, tandis que le second ouvre uniquement l'ordre de travail spécifique à traiter.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FS01b7vaSf3ePt9ZKhwlp%2Fimage.png?alt=media&#x26;token=8e0471ce-5f15-4335-9642-965f56d31f79" alt=""><figcaption></figcaption></figure>


{% endtab %}

{% tab title="Via l'application Manufacturing" %}
Sur la page d'accueil, allez à l'icône « Manufacturing ».

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FtXcdYty56UzWoCp3mxbq%2Fimage.png?alt=media&#x26;token=8fe5597a-ec02-4689-af85-a7abaa1e217e" alt=""><figcaption></figcaption></figure>

Vous pouvez voir ici une liste de tous les Ordres de Fabrication. Utilisez la barre de recherche en haut pour trouver le bon Ordre de Fabrication par sa référence, par le nom du patient, SU[^1] ID ... Veuillez vous assurer de sélectionner la bonne option.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2F2NQNb4AjLxVmBf7fQxlC%2Fimage.png?alt=media&#x26;token=308cab1c-96c7-4aff-aeba-b26b63fdc9b7" alt=""><figcaption></figcaption></figure>
{% endtab %}
{% endtabs %}

### Étapes de l'ordre de travail

À l'intérieur du **Ordre de fabrication**, vous trouverez un onglet appelé **"Ordres de travail"**.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2F59XT3qC8JdgiErqWCtPX%2Fimage.png?alt=media&#x26;token=137f3621-7236-4f10-b412-20e809f13c55" alt=""><figcaption></figcaption></figure>

Cet onglet contient toutes les étapes qui doivent être complétées par l'atelier. L'utilisateur doit progresser à travers chaque étape d'ordre de travail pas à pas avant que le processus de fabrication soit terminé..

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FcjW0yUbQj0VE9JPzp7HJ%2Fimage.png?alt=media&#x26;token=4b14abac-6445-4306-9bd8-6f20726a1bc8" alt=""><figcaption></figcaption></figure>

Chaque étape a un bouton « Démarrer »/« Bloquer ».

·       Lors du démarrage d'un ordre de travail, un chronomètre commencera jusqu'à ce que l'utilisateur « Pause » ou le marque comme « Terminé ».&#x20;

·       Cela aidera à suivre le temps pour chaque étape.

{% hint style="info" %}
Actuellement, une seule personne peut démarrer l'étape même s'il y a plusieurs personnes qui y travaillent.
{% endhint %}

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FiZjXdilBKMdqWOciZTLA%2Fimage.png?alt=media&#x26;token=6d783642-4d58-4b37-a95d-dee838d632ec" alt=""><figcaption></figcaption></figure>

Selon la configuration de votre installation, certaines étapes de l'ordre de travail — telles que Greenlight — peuvent nécessiter une validation obligatoire. Dans de tels cas, seuls les utilisateurs autorisés peuvent approuver l'étape. Pour continuer, l'utilisateur doit cliquer sur le bouton Demander la validation et attendre l'approbation avant de passer à l'étape suivante.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FKmSOG9sfIgbW0wBOT6go%2Fimage.png?alt=media&#x26;token=d6ce15c9-1b5a-4f9b-9cc7-3f3d240723ec" alt=""><figcaption></figcaption></figure>

_Exemple :_

Dans cet exemple, je suis connecté en tant que « Chef clinicien », le seul rôle qui peut approuver cette étape.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FKYesoYFF5t5JobEcNtC6%2Fimage.png?alt=media&#x26;token=dc3faf57-ef9e-43c1-a782-cf5f99045363" alt=""><figcaption></figcaption></figure>

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FH4hiEcVGWv0rwg7pXOc3%2Fimage.png?alt=media&#x26;token=997c53b0-ca2f-40c0-8b6e-fdeed7a63e8c" alt=""><figcaption></figcaption></figure>

### 🗺️ Aperçu visuel&#x20;

{% @mermaid/diagram content="graph LR
 subgraph PW_PO["P&O / Head of P&O"]
        PW_PO_01["Validation"]
  end
    PW_01["Starting the Step"]
    PW_02["Doing the work"]
    PW_03["Is validation step"]
    PW_04["Is Last step"]
    PW_05["Finalize Manufacturing Process"]
    PW_06["Restart Process"]
    PW_07["Close the step"]
    PW_01 --> PW_02
    PW_02 --> PW_03
    PW_03 -- Yes --> PW_PO 
    PW_03 -- No --> PW_07
    PW_04 --> PW_05 & PW_06
    PW_07 --> PW_04
    PW_PO --> PW_07
PW_06
    PW_04@{ shape: diam}
    PW_03@{ shape: diam}
" %}

## Et ensuite ?&#x20;

Après avoir terminé le traitement de l'ordre de travail, l'étape suivante est la **validation de l'ordre de fabrication** pour confirmer que tout est prêt pour l'achèvement de la production.





[^1]: Fournisseur de service

[^2]: Planification des ressources de fabrication
