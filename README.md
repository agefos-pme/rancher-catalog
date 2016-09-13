# rancher-catalog AGEFOS

Contient le catalogue AGEFOS applicatif nginx logstash elasticsearch kibana hadoop

1- Lancer un navigateur web ayant le fqdn / Addr IP ````admin.services.agefos-pme.intra:8080````

  - ![Ecran de chargement](/img/rancher-logo.jpg)

  - ![Ecran de bienvenue](/img/ecran-bienvenue.jpg)

2- Configuration d'enregistrement d'hôte ( premier membre rancher )

  - Cliquer sur le bouton **Add Host**

  - ![Ajout du premier hôte](/img/bouton-add-host.jpg)

    - Sauvegarder la configuration d'enregistrement

    - ![Sauvegarde conf d'enregistrement rancher](/img/registration-host-url.jpg)

      -  Cliquer sur le bouton **Save**

        - ![Ajout d'un hôte](/img/bouton-save.jpg)

        - ![Ecran commande Ajout d'un hôte](/img/ecran-cmd-enregistrement.jpg)

        - Cliquez sur l'icône **Copy to clipboard** pour copier la commande d'enregistrement

          - ![Commande Ajout d'un hôte](/img/cmd-enregistrement.jpg)

          - ![Presse papier](/img/bouton-copy-to-clipboard.jpg)

          - Copier et exécuter cette commande dans le shell du premier hôte rancher **admin**

          - ![Commande shell enregistrement](/img/cmd-shell-enregistrement.jpg)

            - Une fois l'enregistrement du premier membre cliquer sur le bouton **Close**

              - ![Fermeture](/img/bouton-close.jpg)

              Pour les autres membres faire de même seulement lorsque le conteneur nginx sera déployé sur le premier hôte donc plus tard


  3- Ajout du catalogue AGEFOS

    - Cliquer sur le menu **Admin**

    - ![Setting catalogue](/img/admin-menu.jpg)  
