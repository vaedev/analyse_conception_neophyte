# <center> CHAPITRE VI : Le dictionnaire des données</center>

Voici un petit chapitre (mais apréciable) sur le dictionnaire des données : c'est un outil parallèle au MCD. Il permet de lister l'ensemble des informations dans un tableau permettant de décrire de manière précise les informations.

Nous saurons ce que contient une information. Par exemple le type de la donnée pour savoir si on a affaire à un entier, un texte. Nous pourrons détailler le nom d'un champ avec une description perrmettant de clarifier la compréhention du nom. la colone commentaire ajoute des informations utiles pour comprendre la donnée.

exemple d'un dictionnaire des données (tiré de l'exemple précédent dans la présentation du MCD) :

| NOM DU CHAMP  | DESCRIPTION  | TYPE DE DONNÉES |COMMENTAIRE |
| :--------------- |:---------------:| -----:|-----:|
| id_livre |   identifiant unique d'un livre   |entier(11) | numéro généré automatiquement |
| titre | titre du livre  |  alpha numérique(150) | obligatoire |
| nb_page | nombre de page d'un livre   |   entier(11) | nom obligatoire |
| id_auteur | identifiant unique d'un auteur  |   entier(11) | numéro généré automatiquement |
| nom | nom de l'auteur    |   alpha numérique(150) | obligatoire |
|presentation | présentation de l'auteur    |  texte | non obligatoire |

><center> Ressentez le plaisir de ne pas revenir 100 fois sur le même sujet dans une réunion par ce qu'on a oublié ou pas compris les données. Une fois le tableau bien fait, vous pouvez dire en toute tranquillité à votre collègue stressé à outrance et qui vous demande pour la "10e fois, c'est quoi ça au fait ?" Ça ne l'apaisera pas, mais vous pourrez lui répondre "laisse moi aller regarder le dictionnaire des données pour toi". Et être sûr de ne pas être contaminé par son angoisse.

Au niveau des différents types de données, voici une liste "assez" complète et simplifié, en tout cas beaucoup utilisé : 

- Entier : les entiers relatifs (positif et négatif)
- Décimal : nombres à virgule (positif et négatif)
- Alpha numérique : les chaaines de caractères "courtes"
- texte : les textes sans limitation du nombre de caractères
- booléen : ne pouvant prendre que deux valeurs (vrau ou faux / 0 ou 1)
- date : valeur sous le format XX/XX/XXXX

Nous remarquons que certaines données comporte en commentaire "numéro généré automatiquement". Si vous conaissez les BDD cela vous donnes des informations précieuse sur la nature de ces data.
___

<center>Fin du chapitre concernant le dictionnaire des données. Merci d'avoir lu ce didacticiel. Prochain chapitre :

 **"le Modèle logique de données (MLD) et le modèle physique des données (MPD) "**</center>


