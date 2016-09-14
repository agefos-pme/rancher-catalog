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

              - Pour les autres membres faire de même mais après le conteneur nginx

3- Ajout du catalogue AGEFOS

  - Cliquer sur le menu **Admin** puis selecionner **Settings**

  - ![Settings catalogue](/img/admin-menu.jpg)  

  - ![Ecran settings](/img/ecran-settings.jpg)

  - Cliquer sur le bouton **Add Catalog**

    - ![Ecran settings](/img/bouton-add-catalog.jpg)

    - Dans le champs **Name** saisir AGEFOS et dans le champs url **https://github.com/agefos-pme/rancher-catalog/**

      - ![catalogue info](/img/catalogue-saisie.jpg)

      - Cliquer sue le bouton **Save** pour finir

        - ![catalogue info](/img/bouton-save.jpg)

        - Désormais dans le menu **Catalog**, le catalogue **AGEFOS** est disponible et celui-ci contient les applications paramètrées Elasticsearch, Logstash, Kibana et Nginx, il sera alimenté au fur et à mesure

          -  ![catalogue info](/img/catalogue-agefos.jpg)

4- Rendez vous à cette adresse pour la suite **Déploiement conteneur nginx reverse et upstream**

-
