Ce repository reprend les exercices concernant GAZEBO du cours des M1 IN.

Il comprend 3 packages (puckbot_control, puckbot_description, puckbot_gazebo). Les exercices sont repartis dans ces differents packages. Il est important de bien respecter l'ordre des taches. Ceci correspond a une progression logique.

A partir de la tache 09, il convient de modifier le fichier world.launch du package puckbot_gazebo. L'argument "world_name" de la ligne 5 doit etre decommente. Il faut egalement adapter son nom pour les taches suivantes.
Avant de lancer ce fichier launch, il faut egalement mettre a jour la variable d'environnement GAZEBO_RESOURCE_PATH avec que GAZEBO aille bien chercher le world dans le repertoire world du package puckbot_gazebo. Il faut utiliser la commande export et le chemin complet vers le repertoire world (export GAZEBO_RESOURCE_PATH=chemin_complet).