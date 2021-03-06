# Plugin Koha "Transition bibliographique"

Le plugin Koha "Transition bibliographique" est un module optionnel qui peut être ajouté à Koha afin de faciliter l'alignement du catalogue Koha avec les réservoirs nationaux. Une fois les identifiants intégrés comme les clés ARK, les outils de type moissonneur (comme le vendangeur) pourront mettre à jour les notices en se basant sur ces clés.

Il est principalement dédié à la communauté francophone Unimarc afin de simplifier au maximum le processus d'importation avec Koha. L'export des données peut se faire aujourd'hui avec un profil CSV et rapports SQL. L'export peut aussi être réalisé avec un rapport SQL pour récupérer les biblionumber que vous souhaitez puis utiliser le module d'export de Koha en utilisant la liste des biblionumber ainsi obtenue. Vous pouvez lire la [page sur les alternatives](alternatives.md).

Bibliostratus est identifié dans la transition bibliographique comme étant le logiciel libre de référence pour permettre d'aligner les catalogues avec la BnF. Vous pouvez utiliser ce plugin dans le but de traiter votre catalogue avec Bibliostratus.

Il serait possible de travailler uniquement avec le vendangeur développé par BibLibre, cependant le processus et les résultats ne sont pas les mêmes. Une fois les données dans Koha, il sera temps de mettre en valeur ces données liées dans le catalogue. L'idée est de rendre autonome un maximum les utilisateurs Koha intéressés notamment par Bibliostratus.

Suite de la documentation:
* [Import des identifiants](import.md) dans votre catalogue Koha

![Plugin - outil d'export](images/koha-plugins.png)

Ce plugin a été initialement commandé par l'association [Kohala](http://koha-fr.org/) et développé par [BibLibre](http://biblibre.com/). Il est sous [licence libre](../LICENSE).

Pour accéder au plugin, rendez vous sur: Outils > Outil de Plugins >  Bouton "Lancer l'outil" (du dit plugin)

## Une démo en vidéo

### Export de données avec Koha formattées pour Bibliostratus

[![Alt text](https://img.youtube.com/vi/DuLtvby6CR4/0.jpg)](https://www.youtube.com/watch?v=DuLtvby6CR4)

### Exemple d'utilisation de Bibliostratus pour l'alignement

[![Alt text](https://img.youtube.com/vi/k2lwiyoHi9U/0.jpg)](https://www.youtube.com/watch?v=k2lwiyoHi9U)

### Import des données dans Koha

[![Alt text](https://img.youtube.com/vi/iFkCEKJKXVY/0.jpg)](https://www.youtube.com/watch?v=iFkCEKJKXVY4)
