---
description: >-
  La page fournit des instructions sur la gestion des variantes de produit,
  abordant en particulier la manière de traiter les combinaisons d'attributs et
  de valeurs qui ne sont pas réalisables ou dispon
---

# Créer un produit avec variantes

## Configuration d'un produit avec un seul attribut

Lorsqu'un produit possède certains attributs qui le définissent par des différences tout en conservant les données principales au même endroit, nous utiliserons des variantes.\
Nous commencerons par un exemple simple :

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2F1Q6cdLcXq6yHz3iZIVR1%2Fimage.png?alt=media&#x26;token=6cff8c2a-aeba-4034-905a-7748a7778c80" alt=""><figcaption></figcaption></figure>

* 1\. Préfixe de référence / t
* 2\. Masque de référence de variante - lorsqu'un produit possède des variantes, nous configurons un préfixe de code et un masque de référence pour créer le code final du produit (référence) en ajoutant une partie du code décrivant la variante\
  en plaçant le nom de l'attribut entre crochets, le code de chaque variante sera créé automatiquement. REMARQUE : le nom de la variante doit correspondre exactement sinon le système générera une erreur !
* 3\. le nombre de variantes est défini par le nombre d'attributs et de valeurs d'attribut

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2F47YDH8h6LNTF02Qx92ow%2Fimage.png?alt=media&#x26;token=d495da93-39ca-4ac1-a911-d73765a73a77" alt=""><figcaption></figcaption></figure>

Dans cet exemple, le produit n'a qu'un seul attribut (Largeur du pansement) avec 5 valeurs possibles - définissant 5 variantes possibles.

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FuGR7Vfi4DZYLxUlmVwbd%2Fimage.png?alt=media&#x26;token=3100fbee-3660-4f62-957b-da621b0de83d" alt=""><figcaption></figcaption></figure>

Notez que la référence interne de chaque produit est générée conformément au masque de référence de la variante.

{% hint style="danger" %}
**Avertissement :** Si votre produit n'a qu'un seul attribut avec une seule valeur, créez-le sans variantes afin d'éviter une complexité inutile et d'assurer une expérience client simple.
{% endhint %}

## Configuration d'un produit avec plusieurs attributs et valeurs

Lorsqu'un produit est défini avec plus d'un attribut, il créera un produit cartésien des valeurs d'attributs comme nombre final de variantes.

Voici deux exemples :\
Dans cet exemple 2 côtés x 2 tailles créeront 4 variantes.

![](https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FgENSMijJhQIjgUc1OpRy%2Fimage.png?alt=media\&token=caf4797a-bdde-4d96-8161-80c5f7bda4a2) ![](https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FJKEGKAlP8GwFZCpZJ7qm%2Fimage.png?alt=media\&token=0b05c330-fc2c-4f8e-9d28-e8d555392c65)

Dans cet exemple il y a 3 attributs, et le nombre total de variantes est de 24

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FTNB5Js6uZZUOJZhJRL3U%2Fimage.png?alt=media&#x26;token=78384bd9-2a07-436a-b9f5-58bab564e2a1" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Pour les attributs couleur et pointure - il y a plus de valeurs possibles, mais seules les valeurs sélectionnées définiront ce produit (d'autres produits peuvent avoir plus de valeurs de pointure)
{% endhint %}

## Gestion des cas particuliers

Dans certains cas particuliers, lorsque nous avons plusieurs attributs appliqués avec plusieurs valeurs d'attribut, certaines combinaisons ne sont pas possibles/disponibles.

Par exemple, la mousse EVA existe en différentes dimensions de feuilles et épaisseurs, mais\
les feuilles de 3 mm et 6 mm d'épaisseur n'existent qu'en 0,95 m x 0,95 m, tandis que les 12 mm d'épaisseur n'existent qu'en 1,10 m x 1,10 m\
![](https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FXqMvkPH6yyp30J7NpzIH%2Fimage.png?alt=media\&token=3879088c-0853-4ccf-a1a7-f6711c8bdc6c)\
\
Pour cela, nous devons suivre ces étapes :\
1\. Cliquez sur le bouton « Variantes » pour voir toutes les variantes possibles et cocher celles impossibles\
2\. Ensuite, allez dans « Action » > « Archiver » :

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FGILFTUsrUPRzTWIGKvBd%2Fimage.png?alt=media&#x26;token=dcc92632-39d4-4df8-9b43-6fb75800deb4" alt=""><figcaption></figcaption></figure>

Ainsi, enfin, seules les variantes possibles sont visibles dans le système

<figure><img src="https://2479359880-files.gitbook.io/~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FnTWGcVv7ikvz7HIC0Dby%2Fuploads%2FAIyy8QP7BPqnnQVSqZnu%2Fimage.png?alt=media&#x26;token=3488ef75-dcb0-46de-87ae-bf723d684ae6" alt=""><figcaption></figcaption></figure>
