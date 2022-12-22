# I- Membre :

  RAHOUI Imane
  
# II- SI VOUS SOUHAITEZ TESTER LE CODE 

## Il suffit de suivre les étapes suivantes :<br>

  - Installation keycloak-20.0.1<br>
  - run mvn package au niveau du directory keycloakx-custom-theme<br>
  - ajout du .jar au niveau du dossier providers de keycloak<br>
  - lignes de commandes : ```kc.bat config``` et puis ```kc.bat start-dev```<br>
  - creation du realm (ecom-control-realm) et du client (product-app)<br>
  - creation des utilisateurs et des roles<br>
  - lancement des serveurs : Eureka discovery -> gateway puis inventory et customer pour cloturer avec le billing service <br>

# III- CAPTURES DE L'EXECUTION

![1](https://user-images.githubusercontent.com/77898496/209239019-f08fc544-9d98-4bd0-afe5-2825419c15d0.png)

![2](https://user-images.githubusercontent.com/77898496/209239028-69ade4f0-0030-4178-a4e0-a787b16041f5.png)

### PROBLEME AU NIVEAU DU BILLING SERVICE -- BON FONCTIONNEMENT MS AVEC L'AJOUT DE L'ASPET SECURITE - J'AI TROUVE DU MAL A ENVOYER LE TOKEN VERS PRODUCT OU CUSTOMER SERVICE

# IV. BONUS  : (Personnalisation du theme de la page de login keycloak)

![3](https://user-images.githubusercontent.com/77898496/209239041-9859be51-427a-4e2f-af2e-d99c8d6884fe.png)

## BONNE RECEPTION 😊 
