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
  - ref 3 : https://agupubs.onlinelibrary.wiley.com/doi/full/10.1029/2007GL031480  (formule)(bonne source)


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

- On reprend notre programme, au lieu de faire un monde en 3D on a décidé d'opter pour un monde linéaire, car ça n'affecte pas notre sujet et la recherche qu'on veut faire.
