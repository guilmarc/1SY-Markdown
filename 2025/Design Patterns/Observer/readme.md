<p align="Center"><img src="../../includes/logo.png" alt="drawing" width="100"/></p>
<h4 align="Center">1SY - Analyse Objet</h4>

# 🏋🏻‍♂️ ShawiQuest

Dans cet atelier vous devez programmer en deux versions une toute petite partie d'un jeu de rôle.

# Version 1 - Sans patterns

Votre programme devra permettre à l'utilisateur d'appuyer sur `d` pour créer des dommages au joueur ou sur `h` pour guérir, en partie, le joueur.

Voici un exemple d'exécution du jeu en question : 
```plaintext
Press 'd' to take damage, 'h' to heal:

Red Health Bar : 70 (Lost 30 HP)
Play Hurt Sound !

Red Health Bar : 53 (Lost 17 HP)
Play Hurt Sound !

Green Health Bar : 63 (Gained 10 HP)
Play Heal Sound !

Red Health Bar : 34 (Lost 29 HP)
Play Hurt Sound !

Green Health Bar : 46 (Gained 12 HP)
Play Heal Sound !

Red Health Bar : 22 (Lost 24 HP)
Play Hurt Sound !
Green Health Bar : 30 (Gained 8 HP)
Play Heal Sound !
AI Companion: Healing you!

Red Health Bar : 7 (Lost 23 HP)
Play Hurt Sound !
Green Health Bar : 22 (Gained 15 HP)
Play Heal Sound !
AI Companion: Healing you!

Red Health Bar : 0 (Lost 27 HP)
Play Hurt Sound !

Game Over!
```

## Liste des entités de base
### Player
Un joueur avec un nom (`Name`) et une ligne de vie entre 0 et 100 (`HealthPoints`).  Quand le joueur arrive à 0, il meurt.  On peut lui faire des dommages (`TakesDamage`) entre 10 et 40 au hasard et le guérir (`Heal`) entre 5 et 20 au hasard.

### HealthBar
Une classe qui s'occupe seulement d'afficher l'état de santé du joueur dans une barre rouge ou verte conformément à l'exemple d'affichage.

### SoundManager
Une gestionnaire qui s'occupe d'émettre un "son" selon que le joueur a été blessé ou guérit selon l'affichage proposé.

### AICompagnon
Un compagnon AI qui va guérir le joueur s'il commence à être trop faible, moins de 30 points de vie par exemple.

# Version 2 - Avec Design Pattern
Avec la théorie expliqué sur le design pattern en question, programmez la version 2 de l'énoncé précédent mais cette fois-ci, en intégrant le pattern en question.

<hr><p align="Center"><img src="../../includes/end.png" alt="drawing" width="150"/></p>
