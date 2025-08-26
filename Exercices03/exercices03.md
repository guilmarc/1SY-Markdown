<p align="Center"><img src="../includes/logo.png" alt="drawing" width="100"/></p>
<h4 align="Center">1SY - Analyse Objet</h4>

# 🏋🏻‍♂️ Exercices 03 - Modèle du domaine

#### 📁 [Structure à utiliser](../includes/rules.md)

## 👩‍🍳 Question 01 - Les recettes de madame Giblotte
Dessinez le modèle du domaine d’un livre de recette contenant de 50 à 75 recettes contenant ces entités:
- Livre
- Recette
- Ingrédients

## ✍️ Question 02 - OK bye !
Dessinez le modèle du domaine d’un mini système de gestion de condo locatifs contenant ces entités:
- Personne (nom)
- Appartement (adresse)
- Bail (date, renouveller())

## 😄 Question 03 - CSBuddy
d’un réseau social privé nommé `CSBuddy`.  Dans ce groupe un membre (nom & alias) peut se faire de 1 à 5000 amis.  Pour ce qui est des communications, il sera possible, bien entendu, de communiquer à deux mais aussi en groupe (nom & alias).  Nous désirons finalement être en mesure de célébrer les anniversaires d’amitié.

Réfléchissez aux entités nécessaires et aux liens entre eux et dessinez cette partie du modèle du domaine du réseau social.

## 🌳 Question 04 - L'arbre qui regardera vers le ciel.
Dessinez le modèle du domaine de la structure des répertoires et des fichiers de votre ordinateur comprenant ces entités :
- Nœud
- Fichier
- Répertoire

Un fichier est un nœud et un répertoire est un nœud qui est composé de répertoires et de fichiers.

Ajoutez-y correctement les attributs :
- nom : string
- contenu : byte[]

## ✈️ Question 05 - Si j'avais les ailes d'un ange...
Dessinez le modèle du domaine d’une partie d’un système de gestion des vols d’avion incluant ces entités :
- CompagnieAerienne (nom)
- Vol (dateHeureDepart, dateHeureArrivée)
- Aéroport (nom, noIdentification)
- Ville (nom)
- Escale (dateHeureDepart, dateHeureArrivée)

Pour de cas-ci, fiez-vous au fonctionnement de ce type de système dans la vie de tous les jours.

## 🇨🇦 Question 06 - CanadianTire
Dessinez le modèle du domaine d’un système de gestion de vente au détail que vous voudriez vendre au magasin `Canadian Tire`.  Il existe plusieurs succursales à travers le Canada qui ont toutes un inventaire différent.  Nous voulons pouvoir créer des circulaires qui seront identiques pour toutes les succursales.  Prenez en considération que vous voudriez être en mesure de vendre ce même système de gestion à plusieurs autres clients que les Canadian Tire.

## 🇨🇦 Question 07 - CanadianTire Reloaded
Recopiez le diagramme de la question précédente et ajoutez la possibilité d'effectuer des ventes.

<hr><p align="Center"><img src="../includes/end.png" alt="drawing" width="150"/></p>
