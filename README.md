Cette section explique le fonctionnement du projet.

* Ce projet présente 3 roles ansible différent:
  1. Tomcat:
       - installer java
       - d'installer tomcat manuellement
       - créé le service systemd tomcat (tomcat.service)(Démarer le service(handler))
       - changer les paramétres de la jvm
       - sauvegarder les fichier de configuration
       - Deployer des application (.war) avec la méthode des Host
       - redémarer service Tomcat(handler)

  3. Postgresql:
       - Installer les dependences nécessaires
       - installer postgresql
       - demarer service postgres(handler)
       - créé une base de données
       - sauvegarder une base de données (export)
       - restorer une base de données (restore)
  4. lvm:
       - créé des volume physique
       - créé un volume global
       - créé des volume logique
       - formatage des volumes logique
       - créé les points de montage
    
     
