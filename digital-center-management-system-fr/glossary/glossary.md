# Glossaire

#### 🔧 Terminologie MRP / Fabrication

* **MRP (Planification des ressources de fabrication)**: Un système utilisé pour planifier et gérer les processus de fabrication, y compris les stocks, la production et la livraison.
* **BoM (Nomenclature)**: Une liste de toutes les pièces, composants et matériaux nécessaires pour fabriquer un produit.
* **Ordre de travail**: Une tâche spécifique dans le processus de fabrication. Chaque étape (par ex. découpe, assemblage) est généralement un ordre de travail.
* **Ordre de fabrication (OF)**: Une demande de production complète qui inclut toutes les étapes et matériaux nécessaires pour obtenir un produit fini.
* **Centre de travail**: Un lieu physique ou un ensemble de machines où des étapes de fabrication spécifiques ont lieu.
* **Opération**: Une étape du processus de fabrication, souvent assignée à un centre de travail (par ex. « Premier assemblage »).
* **Ordre de production**: Synonyme d'Ordre de fabrication dans ce contexte.

***

#### 🧑‍⚕️ Rôles / Personnel

* **P\&O**: Prothèses et Orthèses — personnel responsable de la création de dispositifs médicaux pour les patients.
* **Opérateur d'atelier**: Un technicien qui construit physiquement les dispositifs (prothèses, orthèses, etc.).
* **SU (Utilisateur du service)**: Le patient ou la personne recevant le dispositif fabriqué.
* **Responsable P\&O / Responsable Clinique**: Un rôle de superviseur qui peut approuver les étapes de fabrication.

***

#### 📦 Gestion des stocks / Inventaire

* **Prélèvement de stock**: L'action de sélectionner et déplacer des produits d'un emplacement à un autre dans l'inventaire.
* **Transfert interne**: Déplacement de stock au sein de la même entreprise (par ex. du dépôt principal à l'atelier).
* **Recasting**: Reconstruire ou modifier un dispositif existant en réutilisant certains composants.
* **Avoir de livraison partielle**: Un ordre de suivi pour livrer les articles restants qui n'ont pas pu être livrés initialement.
* **Numéro de lot/série**: Un identifiant unique pour un produit, particulièrement utile pour la traçabilité (par ex. quel dispositif a été remis à quel patient).

***

#### 📋 Actions système / Concepts d'interface

* **Confirmer**: Approuver une étape pour qu'elle passe à l'étape suivante (par ex. confirmer un ordre MRP).
* **Valider**: Finaliser ou approuver un enregistrement dans le système (par ex. un mouvement de stock, un ordre de fabrication).
* **Vérifier la disponibilité**: Vérifier que des produits ou matériaux existent en stock et peuvent être réservés.
* **Remplissage automatique**: Remplir automatiquement la quantité de composants à utiliser, en fonction de la disponibilité.
* **Case à cocher "Est recasting"**: Un indicateur utilisé pour marquer qu'un mouvement de stock est destiné au recasting.
* **Statut Brouillon**: Statut initial où des modifications peuvent être apportées ; non finalisé.

***

#### 🧭 Navigation / Modules dans Odoo

* **Gestion des utilisateurs de service**: La partie du système où vous gérez les patients (SUs).
* **Application Inventaire**: Le module qui gère les opérations de stock et d'entrepôt.
* **Application Fabrication**: La partie d'Odoo où les ordres et processus de fabrication sont gérés.
