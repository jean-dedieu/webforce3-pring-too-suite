# webforce3-pring-too-suite


### Installler Spring Tools Suite

#### Linux

Étape 1 :  Télécharger le STS tgz depuis le site officiel

           https://spring.io/tools

Étape 2:


           Déplacer le fichier vers  le dossier “/opt”

           sudo mv springFile /opt/

           cd /opt/


Étape 3: 

        Dézipper le le fichier avec “sudo tar  -xvvf”
       
        sudo tar -xvf springFile
       
     
Étape 4:

        Faire une entrée DeskTop pour STS

        ls

        cd STS-4.12.1.RELEASE

        sudo nano /usr/share/applications/STS.desktop

Copier coller cette configuration en l'adapta à votre version:

Name=SpringSource Tool Suite
Comment=Spring Tool Suite
Exec=/opt/sts-4.7.0.RELEASE/SpringToolSuite4
Icon=/opt/sts-4.7.0.RELEASE/icon.xpm
StartupNotify=true
Terminal=false
Type=Application
Categories=Development;IDE;Java;



Windows

Suivre ce tutoriel:

https://www.youtube.com/watch?v=5_mar7HGxeQ


Mac:

https://www.youtube.com/watch?v=yrneL75J3yw






