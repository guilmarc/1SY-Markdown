<p align="Center"><img src="../includes/logo.png" alt="drawing" width="100"/></p>
<h4 align="Center">1SY - Analyse Objet</h4>

# 🏋🏻‍♂️ Exercices 02 - Diagramme de séquence

#### 📁 [Structure à utiliser](../includes/rules.md)

## 📝 Question 01 - Omnivox

Un étudiant se connecte au portail de son collège afin de consulter ses notes. Créez le diagramme de séquence dans PlantUML pour le scénario `nominal` suivant :

1. L’étudiant ouvre l'application mobile Omnivox et tente d'accéder à ses notes.
2. L'application, non authentifiée, renvoie l'écran de saisie d'identifiant.
3. L'étudiant saisit son identifiant et son mot de passe.
4. L'application envoie la requête au serveur qui la relance au système d'authentification provincial (SAP).
5. Le SAP confirme l'authentification.
6. Le serveur renvoie une confirmation d'authentification à l'application.
7. L'application demande au serveur d'obtenir les notes de l'étudiant.
8. Le serveur consulte la base de données et retourne les notes à l'application.

## 📦 Question 02 - QASystem

On s'intéresse ici au système d'assurance qualité d'une entreprise oeuvrant dans le système manufacturier, `QASystem`.

Un employé inspecte une pièce produite à l'aide d'un scanner 3D afin de s'assurer qu'elle réponde bien aux exigences de qualité de base exigées par le client.

Si le système calcule que la pièce est conforme, il en informe l'employé qui scan son numéro de série afin de l'ajouter à la base de donnée de l'inventaire, le cas contraire, il déclenche une procédure de non conformité. Cette procédure étant complexe, elle fait l'objet d'un cas d'utilisation en sois.

Afin de pouvoir effectuer son travail, l'employé doit obligatoirement s'authentifier.

Programmez le diagramme de séquence de ce cas d'utilisation dans PlantUML.

## 🔁 Question 03 - Créativité en boucle

Utilisant votre créativité.  Écrivez une mise-en-situation de votre choix où il serait approprié d'utiliser le principe de répétition.  Programmez ensuite le diagramme de séquence approprié en PlantUML.

<hr><p align="Center"><img src="../includes/end.png" alt="drawing" width="150"/></p>
