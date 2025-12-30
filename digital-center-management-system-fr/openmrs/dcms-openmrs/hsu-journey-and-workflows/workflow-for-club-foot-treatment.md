---
description: >-
  Exemple de scénario pour un utilisateur venant pour une orthèse d'abduction du
  pied nécessitant un suivi (ajustement ou renouvellement). Cette phase concerne
  les CRP fournissant des OAB sans la méthod
---

# Workflow pour le traitement du pied bot

{% hint style="warning" %}
Dans ce scénario ; l'USH ne recevra que l'attelle d'abduction du pied, car le moulage en série (ou Ponseti) sera effectué en milieu médical (avec parfois une ténotomie).
{% endhint %}

Pour un nouvel USH qui aura besoin d'une attelle d'abduction du pied ;

### **Aperçu du flux de service**

1. **Début**
2. **Nouvel USH pour un nouveau service**
3. **Décision initiale après l'inscription**

<mark style="color:orange;">Sélectionner un nouveau service</mark>

4. **Évaluation initiale**
5. **Sélection de l'affection :**
   * _Malformations congénitales et déformations du système musculo-squelettique (Q65–Q79)_
   * → **Talipe équinovarus**
6. **Résultat initial et définition des objectifs**

<mark style="color:orange;">Planifier le service : USH éligible</mark>

7. **Plan de service de base**
8. **Sélectionner la catégorie de service :**
   * _Orthèse et attelle d'abduction du pied_
9. **Évaluation de la capacité financière (+ évaluation socio-économique et décision de financement)**

<mark style="color:orange;">Approuver le service</mark>

10. **Services**

* Remplir le formulaire pertinent (dans notre scénario nous sélectionnons le premier en gras).
  * **Dossier de traitement du pied bot, évaluation et suivi du plâtre** _Vous pouvez remplir plusieurs formulaires pour permettre le suivi du score de Pirani ._
  * Dossier de traitement du pied bot décision de ténotomie
  * Dossier de traitement du pied bot suivi post-ténotomie
  * Résultats fonctionnels du pied bot après ténotomie

11. **Processus de demande de matériel :**

* Sélectionner Demande de Matériel dans ODOO
* Utiliser le tableau de bord PRP → Ajouter une attelle d'abduction du pied

12. **Résultat final de l'évaluation et définition des objectifs**

<mark style="color:orange;">Clore l'épisode de service</mark>

13. **Rendez-vous pour le service de suivi**

L'USH revient pour la visite de suivi, et aura différentes options via ce flux de travail "suivi" : voir ci-dessous les options.

**Pour ce scénario clinique spécifique, nous pouvons rationaliser le processus en permettant une exception de renouvellement de l'attelle d'abduction du pied dans le flux de travail pour faciliter le travail du clinicien.**

{% hint style="warning" %}
A : Pour la surveillance, les changements de chaussures, l'ajustement, la réparation ou le renouvellement d'une attelle d'abduction du pied dans un délai de 1-2 semaines, l'épisode de service peut se clôturer en fin de mois pour inclure les visites de suivi.
{% endhint %}

{% hint style="warning" %}
B : Maintenir l'activité de l'USH (en gardant l'épisode de service en visite active) pendant 4 semaines entre la 1re et la 3e attelle pour faciliter les ajustements du PRC et des aidants.

Si les problèmes persistent, envisager un retour pour un nouveau plâtre.

* Si les visites de suivi sont espacées de trois semaines ou plus, ou tombent sur des mois différents, l'épisode doit être clôturé.
{% endhint %}

1. **Démarrer l'EoS**
2. **Décision initiale après l'inscription**

<mark style="color:orange;">Sélectionner suivi</mark>

3. **Évaluation du suivi du service**

<mark style="color:orange;">Décision de suivi</mark>

**Traitement du pied bot par appareillage**

<mark style="color:orange;">**OPTION 1 :**</mark> _Ajustement_ OU _Réparation_

<mark style="color:orange;">**OPTION 2**</mark><mark style="color:orange;">:</mark> _Renouveler_

* Barre
* _Changer la pointure_
* _Attelle d'abduction du pied_

4. **Évaluation de la capacité financière - suivi (+ socio-économique déjà fait / décision de financement)**

<mark style="color:orange;">Approuver pour le service</mark>

5. **Dossier de traitement du pied bot, suivi de l'observance de l'attelle**

* <mark style="color:orange;">Décision sur la taille de l'attelle</mark>
  * Si **Bon** → aller à **Plan de suivi du service** (OPTION 1 comme suivi sous Traitement du pied bot par appareillage)
  * Si **À changer** → aller à **Demande de matériel puis plan de suivi du service**

6. **Plan de suivi du service**

<mark style="color:orange;">Avons-nous des dispositifs à réparer lors de cette visite ?</mark>

* Si Non (si option 2) → Enregistrer et valider
* Si Oui (si option 1) :
  * Sélectionner le dispositif et le type de réparation
  * Orthèse / MI bilatéral
  * Ajustement ou réparation

7. **EoS (Fin de service)**
