# Information caractère

* Auteurs: Cyrille Bougot
* Compatibilité NVDA : 2017.3 à 2019.3
* Télécharger [version stable][1]
* Télécharger [version de développement][2]

Cette extension permet d'afficher dans un message des informations sur un caractère telles que nom Unicode, numéro, catégorie, etc.


## Commandes

* PavNum2 (toutes les dispositions de clavier) ou NVDA+, (disposition ordinateur portable): un quadruple appui, affiche des informations sur le caractère de l'objet navigateur courant à la position du curseur de revue.


## Notes

* Cette extension fournit également un script pour afficher directement les informations sur le caractère du curseur de revue. Ce script n'a pas de geste par défaut associé. Si vous n'êtes pas à l'aise avec le geste de commande à 4 appuis, vous pouvez lui assigner un geste de commande dans la boîte de dialogue de geste de commande de NVDA (catégorie "Revue de texte").
* Les informations fournies sont en anglais car elles font partie de la norme unicode. Si une traduction locale existe pour cette extension les informations sont également fournies parallèlement à l'anglais.
* Le nom CLDR (référentiel de données local commun Unicode) est uniquement pris en charge sur NVDA 2019.1 et versions ultérieures.
* Pour les caractères écrits avec les polices propriétaires Microsoft Symbol, Wingding (1, 2, 3) et Webding, des informations supplémentaires sont fournies: nom du caractère, nom de la police et informations du caractère unicode correspondant.


## Journal des changements

### Version 1.3

* Corrige un bug avec NVDA 2019.3.


### Version 1.2

* Fournit des informations supplémentaires sur les caractères écrits avec les polices Microsoft.


### Version 1.1

* Mise à jour pour le support des nouvelles versions de NVDA (compatible Python 2 et 3)
* Release effectuée désormais avec appveyor


### Version 1.0

* Version initiale

[1]: https://addons.nvda-project.org/files/get.php?file=chari

[2]: https://addons.nvda-project.org/files/get.php?file=chari-dev
