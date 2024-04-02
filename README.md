Cette section explique le fonctionnement du projet.

* Ce projet présente 3 roles ansible différent:
  1. Tomcat:
       - installer java
       - d'installer tomcat manuellement
       - créer le service systemd tomcat (tomcat.service)(Démarer le service(handler))
       - changer les paramétres de la jvm
       - sauvegarder les fichier de configuration
       - Deployer des application (.war) avec la méthode des Host
       - redémarer service Tomcat(handler)

  3. Postgresql:
       - Installer les dependences nécessaires
       - installer postgresql
       - demarer service postgres(handler)
       - créer une base de données
       - sauvegarder une base de données (export)
       - restorer une base de données (restore)
  4. lvm:
       - créer des volume physique
       - créer un volume global
       - créer des volume logique
       - formatage des volumes logique
       - créer les points de montage
    
     
