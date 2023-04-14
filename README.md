# albedo.github.io
 **ALBEDO**
 Membres du projet :
 - Louis
 - Asmar
 - Kairui

Descriptif du projet :


Semaine 10 mars :
- Définition détaillée de la problématique : Comment la température peut-elle évoluer en fonction de l'albedo et pk c'est un effet rétroactif?
- Recherche documentaire sur les modèles existants :
  - ref 1 : https://doi.org/10.1215/22011919-9320266 source bien mais court.
  - ref 2 : https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/2014RG000449 (bonne source) mais moins bien que la 3.
  - ref 3 : https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2007GL031480  (formule)(bonne source) albedo.github.io albedo.github.io albedo.github.io

semaine du 17 mars:
- liens :
  - https://www.sciencedirect.com/topics/earth-and-planetary-sciences/albedo
  - https://www-sciencedirect-com.accesdistant.sorbonne-universite.fr/topics/earth-and-planetary-sciences/interfacial-energy
  - https://reader.elsevier.com/reader/sd/pii/B9780124095489103719?token=ED1EBD3BAE3E1BA50BFC8195BF8326E4C3BCCEA7FD1F99C1AEEA14D3C57203ECCA64AF90E488A754D8EBD6F73408210E&originRegion=eu-west-1&originCreation=20230317082452
  - https://curry.eas.gatech.edu/Courses/6140/ency/Chapter9/Ency_Atmos/Reflectance_Albedo_Surface.pdf

- idéeeeees du programme: 
  - création d'un monde(environnement) de taille 3\*3;
  - initialisation du monde avec full -1;
  - la fonction aura pour paramètres des surfaces, 3 pour l'instant;
  - on changera a surface du monde par les surfaces qu'on aura mis en paramètres, exemple :
     - glace = 1,
     - eau = 2,
     - surface à faible albdeo = 3;
  - création d'une nouvelle fonction qui modifie le monde en fonction de l'albedo et de la chaleur(paramètres : monde, fonction albedo,...);
  - on a commencé le programme et créer le monde.

semaine du 25 mars :
- https://www-sciencedirect-com.accesdistant.sorbonne-universite.fr/science/article/pii/B9780080454054006030
- https://tc.copernicus.org/articles/14/1651/2020/

- on a trouvé la formule pour la chaleur;
- on a trouvé un article qui prouve que le Soleil c'est chaud et ça fait sécher ou fondre la glace. 

semaine du 31 mars:
- On a fini notre carnet de bord, on reprend le programme qu'on a laissé en standby et puis on a trouvé un artcile intéréssant qui parlait de la symétrie de l'albedo terrestre.
-Pour le programme on compte utiliser les formules trouvé puis faire des graphiques au début, puis on a une idée de comment créer la fonction de la température pour étudier la conséquence de celle ci et l'effet boule de neige. 

semaine du 7 avril:

- On a changé tout ce qu'on avait fait avant, on a changé les paramètres et les données de base.
- On reprend notre programme, au lieu de faire un monde en 3D on a décidé d'opter pour un monde linéaire, car créer un monde en 3D n'affecte pas notre sujet et la recherche qu'on va faire.
- On a décidé de faire un tableau de dimension 1 avec les tailles surface au lieu de le représenter par un chiffre, car nous allons faire une fonction reflet qui va calculer l'albedo de notre monde, et donc on va utiliser les pourcentages de surface de la Terre c'est-à-dire qu'on va prendre 70 unités d'eau 10 unité de glace et 20 unités d'autres albédo moins fort. Au total il y aura 100 unités pour le monde. (Mais on peut faire des tests avec 80 unités de surface de glace, on pourra s'intéresser au autre cas pour observer comment juste changer les unités d'une surface peut changer le monde (effet boule de neige))
- Ensuite après avoir fait cette fonction nous avons commencé la fonction température qui permet de calculer la température du monde avec une température de base, puis elle va permettre aussi de calculer le réchauffement de la terre et si température trop haute fonte des glaces et réchauffement de l'eau avec l'augmentation du pH (mais cela n'est pas notre étude). Quand la glace va fondre l'eau va augmenter d'une unité par unité de glace fondu et à partir de 5 unités d'eau augmenté, la surface others sera réduit de 1 et on augmentera l'eau de 1.
- On a une idée de créer la fonction 'fonte' on ne connaît pas encore le nom, qui va se consacrer à faire chauffer ou réduire la température qui va permettre de soit faire fondre la glace ou d'augmenter la surface de glace.
- On va ensuite créer une fonction moyenne température qui permettre de renouveler la température de base de notre monde et puis on peut faire une boucle à l'intérieur de cette fonction qui va permettre de calculer la température au bout de x temps (qu'on va mettre en paramètre).
- on s'est arrêté à la fonction température.

semaine du 14 avril:

- On reprend où on s'est arrêté, on essaye de finir la fonction température (on va mettre en paramètre le température moyenne avant de lancer la fonction, puis le monde, et le nombre de jours).
- 
