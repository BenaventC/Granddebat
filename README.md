# Grand Débat National - notes de recherche.

Ce repo contient les fichier *.rmd des procédures r mises en place pour analyser les données du Grand Débat Nntional. On se focalise sur la partie 4 : "organisation de l'Etat et des services publics" qui correspond à un ordre de grandeur de 100 000 contributions.

L'objet de notre projet est de d'analyser comment les représentations de l'Etat et de sa gestion sont produites au travers d'un dispositif de civic tech où biais de sélection et biais de cadrage sont considérables. Pour une [première approche du sujet](https://docs.google.com/presentation/d/183XBYjmdz5Jl4aeijg278eBBJWiSdLZox1Vnvt7zMZw/edit?usp=sharing) ainsi qu'une [carte de visite](https://docs.google.com/presentation/d/1f3QoEF_f7eXP-IBlNo5MnzE_itEcy9f09EZEnSC7GS8/edit?usp=sharing)

Le code est reproductible, il demande simplement de télécharger les données disponibles sur le site du [Grand Débat en OpenData](https://granddebat.fr/pages/donnees-ouvertes) -  choisir le jeu de donnée au 21 mars- et la [carte des départements](http://osm13.openstreetmap.fr/~cquest/openfla/export/departements-20180101-shp.zip).

1 - >[Eléments de cadrage](https://benaventc.github.io/Granddebat/GD01_Intro_cadrage.html) : on utilise trois des questions binaires pour fixer les positions des contributeurs en termes de jugement de la facilité d'accès des services publics, de préférence pour la décentralisation et l'attitude favorable à l'autonomie des fonctionnaires de terrain. On retrouve le vieux dilemme de la théorie des organisations : organique ou mécanique. 

2 - >[Analyse du sentiment](https://benaventc.github.io/Granddebat/GD02sentiment02copie.html) : on joue avec le sentiment, la polarité les émotions. Essentiellement avec l'outil NRC. Le sentiment qui se dégage est bien moins véhément que ce qu'on aurait du attendre. Les biais de participations jouent à plein sans doute. Le constructif dominerait-il le vindicatif?

3 - >[Topic model avec LDA]() - à venir avec solution ldavis.

4 - >[Dynamique de la production]() - à venir. dans quelle mesure la médiatisation peut affecter la production des contenus (ex LBD)