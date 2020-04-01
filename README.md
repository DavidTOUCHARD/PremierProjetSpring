# PremierProjetSpring

Bonjour, voici ma premiere application avec le Framework Spring. Elle dispose de deux lanceurs :

- Lanceur -> version sans annotation (fichier XML  dans resources : demospringinjection.xml)

- LanceurConfig -> version avec annotation (annotation dans ConfigurationBeans.java)




Methodo :
1 creer un projet maven quickstart
2 ajouter dependance spring framework
3 creer des classes dao et service
4 creer le fichier xml conteneur
5 declarer classe dao et service dans le conteneur
6 créer une classe principale
7 mettre en oeuvre l'approche dynamique
	load le conteneur
	recupéreration du bean service
	manipulation du bean service (lecture d'un élève dont l'identifiant 1)
