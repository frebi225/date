# Exercices JavaScript, CSS & HTML

Ce dossier contient quatre exercices pratiques en **HTML, CSS et JavaScript**, chacun illustrant différentes fonctionnalités interactives côté client.

---

## 1. Calculateur de prêt hypothécaire

**Fichier :** `calculateur.html`  

### Objectif
Permettre à l'utilisateur de calculer les mensualités d'un prêt hypothécaire en fonction du montant, du taux d'intérêt annuel et de la durée du prêt.

### Fonctionnalités
- Saisie du **montant du prêt**, du **taux d'intérêt annuel** et de la **durée du prêt** (en années).
- Calcul de :
  - La mensualité (`M`)
  - Le montant total payé
  - Le total des intérêts
  - Le nombre de paiements
- Affichage des résultats de manière claire.
- Validation des entrées utilisateur pour éviter les valeurs incorrectes.
- Possibilité de calculer avec la touche **Entrée**.

### Formule utilisée
M = P × (r × (1 + r)^n) / ((1 + r)^n - 1)
- M : mensualité  
- P : montant du prêt  
- r : taux d'intérêt mensuel (taux annuel / 12 / 100)  
- n : nombre total de paiements (années × 12)  

---

## 2. Manipulation de tableaux

**Fichier :** `tableaux.html`  

### Objectif
Permettre à l'utilisateur de manipuler un tableau de nombres via l'interface web.

### Fonctionnalités
- Affichage du tableau initial `[5, 2, 8, 1, 9, 3]`.
- Ajouter un élément à la fin du tableau.
- Supprimer un élément spécifique du tableau.
- Trier le tableau par ordre croissant.
- Validation des entrées et messages d'erreur en cas de saisie incorrecte.
- Mise à jour dynamique du tableau après chaque opération.

---

## 3. Manipulation de dates

**Fichier :** `manipulation.html`  

### Objectif
Analyser une date saisie par l'utilisateur et calculer sa différence avec la date actuelle.

### Fonctionnalités
- Saisie d'une date au format `JJ-MM-AAAA`.
- Extraction et affichage des composants :
  - Jour
  - Mois
  - Année
- Calcul de la **différence en jours** avec la date du jour.
- Indication si la date est dans le **passé**, le **futur** ou **aujourd'hui**.
- Gestion des erreurs pour les formats invalides ou les dates incorrectes.

---

## 4. Heure en temps réel

**Fichier :** `temps_reel.html`  

### Objectif
Afficher l'heure système en temps réel avec mise à jour automatique chaque seconde.

### Fonctionnalités
- Affichage de l'heure au format `HH:MM:SS`.
- Affichage de la date complète (jour de la semaine, jour, mois, année).
- Mise à jour dynamique chaque seconde avec JavaScript.
- Interface stylée avec un affichage digital et visuel clair.

---

## Technologies utilisées
- **HTML5** : Structure des pages
- **CSS3** : Mise en forme et design responsive
- **JavaScript** : Interactivité et calculs côté client

---

## Instructions d'utilisation
1. Ouvrir l'un des fichiers HTML dans un navigateur moderne (Chrome, Firefox, Edge…).
2. Suivre les instructions spécifiques à chaque exercice affichées sur la page.
3. Interagir avec les formulaires, boutons et champs pour voir le résultat en temps réel.

---

> Ces exercices sont idéaux pour pratiquer la manipulation de **DOM**, la gestion des **événements**, le **calcul dynamique** et la validation des **entrées utilisateur** en JavaScript.


## ✍️ Auteur
👩‍💻 **KOMENAN Audrey Bénédicte**