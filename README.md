# Titre : Budget Calculator - une application React.js pour gérer les dépenses

## Explication de l'application :

L'application "Budget Calculator" est une application simple qui permet aux utilisateurs de gérer leurs dépenses. Elle est développée en utilisant la bibliothèque React.js, qui est populaire pour la création d'interfaces utilisateur interactives et réactives.

La fonction principale de l'application est de permettre aux utilisateurs d'ajouter, de modifier et de supprimer des éléments de dépenses, ainsi que de calculer le total des dépenses. L'application est composée de plusieurs composants React qui travaillent ensemble pour fournir une interface utilisateur conviviale.

## Composants principaux de l'application :

1. `ExpenseForm` : Ce composant est responsable de la saisie des détails de la dépense, tels que le nom de la dépense et le montant. Il contient un formulaire où les utilisateurs peuvent entrer ces informations et les soumettre.

2. `ExpenseList` : Ce composant affiche la liste des dépenses ajoutées. Il reçoit les données des dépenses sous forme de tableau et les affiche sous forme de liste. Chaque élément de la liste comprend le nom de la dépense, le montant et des boutons pour éditer ou supprimer l'élément.

3. `Alert` : Ce composant est utilisé pour afficher des messages d'alerte à l'utilisateur. Il peut afficher différents types d'alertes, tels que des succès, des erreurs, etc.

Fonctionnalités principales de l'application :

- Ajout d'une dépense : Les utilisateurs peuvent entrer le nom de la dépense et le montant correspondant dans le formulaire. Une fois soumis, la dépense est ajoutée à la liste des dépenses.

- Modification d'une dépense : Les utilisateurs peuvent modifier une dépense existante en cliquant sur le bouton "Modifier" correspondant à cette dépense dans la liste. Les détails de la dépense sélectionnée sont pré-remplis dans le formulaire, permettant aux utilisateurs de les modifier. Une fois les modifications apportées, les données sont mises à jour dans la liste.

- Suppression d'une dépense : Les utilisateurs peuvent supprimer une dépense en cliquant sur le bouton "Supprimer" correspondant à cette dépense dans la liste. Une fois supprimée, la dépense est retirée de la liste.

- Calcul du total des dépenses : Le total des dépenses est affiché en haut de la page. Il est calculé en additionnant tous les montants des dépenses dans la liste.

- Gestion des alertes : L'application affiche des messages d'alerte pour informer les utilisateurs des actions réussies ou des erreurs. Les alertes sont affichées pendant une courte période de temps avant de disparaître.

- Stockage des données : Les dépenses sont stockées localement en utilisant l'API `localStorage`. Cela permet de conserver les données même si l'utilisateur recharge la page ou quitte l'application.

L'application utilise également la bibliothèque `uuid` pour générer des identifiants uniques pour chaque dépense ajoutée.

En résumé, l'application "Budget Calculator" est une application simple mais utile pour gérer les dépenses. Elle offre des fonctionnalités d'ajout, de modification et de suppression de dépenses, ainsi que le calcul du total des dépenses. Elle est développ

ée en utilisant React.js, ce qui permet une expérience utilisateur réactive et interactive.


![Capture d’écran 2023-06-25 à 17 35 36](https://github.com/Ilyas-44/budget-calculator/assets/117936276/0044dd99-801d-4cd7-97cd-0742c99b0dd8)


