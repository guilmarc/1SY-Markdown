<p align="Center"><img src="../includes/logo.png" alt="drawing" width="100"/></p>
<h4 align="Center">1SY - Analyse Objet</h4>

# Exercices 01 - UCD

#### 📝 Lien vers les [notes de cours](https://slides.com/hkoncept/1sy-02/fullscreen?token=RthcbPo9).

## Structure à utiliser
1. Créez un dossier (ou dépôt github) principal nommé `1SY-AnalyseObjet` et ajoutez-y un sous-dossier `UML`.
2. Créez un répertoire `Exercices01`.
3. Pour chacune des questions, ajoutez-y un fichier portant le nom de la question et inscrivez-y la réponse :
   1. Un `.txt` pour une question textuelle.
   2. Un `.wsd` pour écrire du code PlanUML.
 > Exemple: `question02.1.wsd`

## Question 01 - James le pompiste

Considérons une station-service de distribution d'essence. Les clients se servent de l'essence et le camionneur-pompiste remplit les cuves.

1. Le client se sert de l'essence de la façon suivante : il prend un pistolet accroché à une pompe et appuie sur la gâchette pour prendre de l'essence. Qui est l'acteur du système ? Est-ce le client, le pistolet ou la gâchette et pourquoi ?
2. James, dont le métier est pompiste, peut se servir de l'essence pour sa voiture. Pour modéliser cette activité de James, doit-on définir un nouvel acteur ? Comment modélise-t-on ça en PlantUML ?
3. Lorsque James vient avec son camion-citerne pour remplir les réservoirs des pompes, est-il considéré comme un nouvel acteur ? Comment modélise-t-on cela ?
4. Certains pompistes sont aussi qualifiés pour opérer des opérations de maintenance en plus des opérations habituelles des pompistes telles que le remplissage des réservoirs. Ils sont donc réparateurs en plus d'être pompistes. Comment modéliser cela ?

## Question 02 - Les relations
Considérez les besoins suivants :
- Passer une commande (parfois urgente).
- Authentifier.
- Expédier une commande.

Passer une commande urgente est un cas particulier de passer une commande. Pour passer une commande, il faut nécessairement authentifier l'utilisateur.

Codez le diagramme de cas d'utilisation associé en y ajoutant un acteur principal.

<hr><p align="Center"><img src="../includes/end.png" alt="drawing" width="150"/></p>
