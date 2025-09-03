# Gestion du centre d'admission

Pour gérer les centres, vous devez appartenir au groupe d'utilisateurs OeHealth / Center manager\
Le gestionnaire de centre tient la liste des centres de rééducation, des bâtiments, des services et des lits, des options et d'autres\
données liées à la gestion des centres d'hébergement

**Modèles de données**

**·       Options des centres**

\
Accès au menu : OeHospital -> Configurations -> OeHFieldOptions -> Options\
Contient la liste générale des options disponibles pour les centres. Peut être étendue selon les besoins.\
Champs :

* Nom ou code - l'un ou l'autre de ces champs doit être renseigné.
* Type d'option - utiliser "Options des centres d'hébergement" (d'autres types seront décrits dans l'utilisation)
* Produit lié - non nécessaire, sauf si la facturation est utilisée (utilisation expliquée dans la section Facturation)
* Construction du nom - Comment le nom de cette option sera affiché dans l'interface utilisateur\
  \- (options disponibles : Nom, Code, Code - Nom)\
  \- il est aussi possible d'ajouter d'autres options de construction

\- Les options sélectionnées comme disponibles au niveau du Centre seront propagées comme options au niveau du bâtiment\
\- Les options sélectionnées comme disponibles au niveau du bâtiment seront propagées comme options au niveau du service\
\- Les options sélectionnées comme disponibles au niveau du service seront disponibles comme attributs/options au niveau du lit

**·       Centres de rééducation**

Accès au menu : OeHospital -> Management -> CenterManagement -> Centers\
Champs :

*
  * Partenaire associé - généralement le même partenaire que le partenaire principal de la société, mais peut aussi être un autre partenaire (comme l'adresse de contact du partenaire principal ou tout autre)
  * Nom - nom du centre (utilisé dans ce module)
  * Code - code de ce centre (unique, utilisé pour générer le code du LIT)
  * Genre - Utilisé pour imposer la sélection du genre sur l'entité. La propagation de cette sélection s'applique à tous les objets subordonnés, de sorte que Mixte accepte tout genre, et Masculin/Féminin n'acceptent/autorise que ce genre pour l'admission du patient
  * Séquence d'admission - Séquence utilisée pour attribuer des numéros aux admissions confirmées.\
    \- la séquence peut être définie sur n'importe quel sous-modèle (bâtiment, service, lit) si nécessaire.

o   Options : Sélectionnez les options disponibles dans ce Centre\
Seules les options sélectionnées seront visibles sur le bâtiment comme options à sélectionner

**·       Bâtiment du centre**

Accès au menu : OeHospital -> Management -> CenterManagement -> Buildings\
Champs :

* Centre - sélectionnez le centre auquel appartient ce bâtiment. Appliquera également les options sélectionnées comme disponibles. Si aucune option n'est activée sur le centre sélectionné, l'onglet Options n'est pas visible du tout.
* Nom - nom du bâtiment
* Code - code de ce bâtiment (unique, utilisé pour générer le code du LIT)
* Genre
* Séquence - peut être laissée non sélectionnée si définie au niveau du centre, en cas de besoin de séparer l'énumération des admissions

**·       Service**

Accès au menu : OeHospital -> Management -> CenterManagement -> Wards\
Champs

**·       Lit**

Accès au menu : OeHospital -> Management -> CenterManagement -> Bed\
Champs :\
\


*
  * Code
  * Service
  * Genre

&#x20;
