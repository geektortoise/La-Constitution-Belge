# La Constitution belge (FR)

Vous trouverez dans ce projet GitHub, le texte de la Constitution belge ainsi que l'historique de ses modifications.
Au sein de cet espace, vous aurez la possibilité de consulter la Constitution ainsi que son évolution au fil du temps dans un format favorisant le confort de lecture. De plus, chaque modification de la Constitution peut être consultée, comparée et analysée individuellement.


La Constitution belge est disponible en version consolidée officielle à l'adresse suivante : [http://www.ejustice.just.fgov.be/eli/constitution/1994/02/17/1994021048/justel](http://www.ejustice.just.fgov.be/eli/constitution/1994/02/17/1994021048/justel).

Malgré l'attention particulière apportée à ce projet, diverses coquilles ou erreurs peuvent être présentes. N'hésitez pas à le signaler notamment en ouvrant un ticket (*Issue*) sur cet espace ou en envoyant un mail à team@openjustice.be.
Nous rappelons que les textes présents dans ce projet n'ont pas de garantie légale, le Moniteur Belge seul faisant foi.

## Description

La Constitution belge est encodé dans le fichier Markdown (*constitution.md*) permettant une lecture confortable ainsi qu'une visualisation simple des différences entre les versions d'un même texte.

Le but de ce projet étant de lister les versions successives de la Constitution au fur et à mesure des modifications entrant en vigueur, chacune d'entre elles est considérée comme une modification distincte et pourra être consultée, comparée et analysée en tant que telle.

Afin d'une meilleure lisibilité, les annotations de modifications ne sont donc pas reprises, ces informations étant présentes dans les meta-données de la modification (*commit*) même.


## Utilisation
### Consultation
Il vous suffit de cliquer sur le fichier *constitution.md*. Vous pourrez ainsi directement consulter la Constitution depuis votre navigateur.

![image](https://user-images.githubusercontent.com/8018298/147814615-7b657d03-451f-4b8e-8515-99465143ddc8.png)

### Visualisation des modifications survenues au fil des versions

La liste des modifications apportées à la Constitution est disponible en suivant [ce lien](https://github.com/geektortoise/La-Constitution-Belge/commits?author=noreply@lachambre.be).

![image](https://user-images.githubusercontent.com/8018298/147814721-aef9a42c-cc14-48f5-a933-3d93ca45cfca.png)

Vous y trouverez, par ordre anti-chronologique, la publication initiale, datée du 20 juillet 1831, suivie de l'ensemble des modifications ayant eu lieu. Chaque modification renseigne la date d'entrée en vigueur de la modification concernée.

En cliquant sur le lien relatif à la *Modifications entrées en vigueur le 30-03-2021*, nous avons un aperçu des modifications apportées par la [loi du 17 mars 2021](http://www.ejustice.just.fgov.be/eli/loi/2021/03/17/2021201324/justel) et étant entrées en vigueur le 30-03-2021.

![image](https://user-images.githubusercontent.com/8018298/147815053-8e5fa443-5008-4036-b4c7-b5e3511619ca.png)


À noter que certaines modifications sont trop importantes que pour être prévisualisées et qu'il sera donc nécessaire de cliquer sur *Load diff*

![image](https://user-images.githubusercontent.com/8018298/147815110-285359bb-45ce-4b53-92a7-f66857b7fc55.png)

### Consultation d'une version précise du texte

Pour consulter le texte en vigueur après une modification, reprennez la [liste des modifications](https://github.com/geektortoise/La-Constitution-Belge/commits?author=noreply@lachambre.be), et cliquez sur le symbole ![image](https://user-images.githubusercontent.com/8018298/90319676-8f177d80-df3a-11ea-8589-6a168910b33b.png) présent à droite de la modification identifiée.

Pour consulter le texte en vigueur à une date donnée, consultez le texte à la version antérieure la plus proche. Dans notre exemple, pour consulter la Constitution en vigueur à la date du 2 février 2020, la version à visualiser sera celle datée du 2 mai 2019.


## Motivation

La principale motivation de ce projet a été de pouvoir mettre à disposition du plus grand nombre un accès aisé à la Constitution belge dans un format directement lisible.
À cette fin, les annotations relatives aux modifications effectuées au fil des versions, comme l'exemple suivant, ne sont pas reprises au sein du texte afin de permettre un meilleur confort de lecture.  
 `[1 ...]1`  
`(1)<L 2014-01-06/45, art. 1, 070; En vigueur : 31-01-2014> `

De plus, suivant la philosophie du logiciel libre, les données et méta-données encodées et structurées pourront librement être réutilisées au sein d'autres projets.

Ce projet a été réalisé dans le cadre du projet [OpenJustice.be](https://openjustice.be/) ayant pour but social le soutien, la sensibilisation et la promotion d'une informatisation de la Justice et du Droit transparente et ouverte.


## Références
- [Version à jour de la Constitution sur le site de La Chambre](https://www.dekamer.be/kvvcr/pdf_sections/publications/constitution/GrondwetFR.pdf)
- Cindy Regnier, [La Constitution au fil de ses versions](https://www.crisp.be/librairie/catalogue/1990-constitution-au-fil-de-ses-versions-9782870752005.html), CRISP



## Pour plus d'information
- Vous trouverez sur [cette page wikipedia](https://fr.wikipedia.org/wiki/Markdown) une description du langage Markdown utilisé ici.
- Voici un [court article](https://medium.com/@koffisani/pourquoi-vous-devez-apprendre-git-aujourdhui-df773a7e1159) expliquant l'utilité de git, le logiciel qui permet l'historisation des versions du Code sur ce site.
- Un [fil de discussion](https://twitter.com/TheGeekTortoise/status/1476861226097463296) Twitter a été ouvert concernant ce projet.
- Ce projet a été rendu possible grace aux outils développés par [Openjustice.be](https://openjustice.be/) et notamment [celui-ci](https://github.com/openjusticebe/be_law_tools).
- Ce projet a été inspiré par une [initiative similaire concernant le Code Civil Français](https://github.com/steeve/france.code-civil/).


## Contraintes techniques
Pour des raisons purement techniques, les modifications ayant eu lieu avant l'année 1970 sont datées au 1er janvier 1970. La date réelle d'entrée en vigueur est néanmoins encodée dans le message de la modification.

