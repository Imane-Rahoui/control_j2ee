# I- Membre :

  RAHOUI Imane
  
# II- SI VOUS SOUHAITEZ TESTER LE CODE 

## Il suffit de suivre les étapes suivantes :<br>

  - Installation keycloak-20.0.1<br>
  - creation realm / client [config ci dessous]/ user / attribution roles ( USER / ADMIN ) au user 

   ![keycloak](https://user-images.githubusercontent.com/77898496/214346530-2506bf61-3ee5-4ef5-8ea3-a09bf46ba51d.png)

  - run mvn package au niveau du directory keycloakx-custom-theme<br>
  - ajout du .jar au niveau du dossier providers de keycloak<br>
  - lignes de commandes : ```kc.bat config``` et puis ```kc.bat start-dev```<br>
  - creation du realm (ecom-control-realm) et du client (product-app)<br>
  - creation des utilisateurs et des roles<br>
  - lancement des serveurs : Eureka discovery -> gateway puis inventory et customer pour cloturer avec le billing service <br>

# III- CAPTURES DE L'EXECUTION
<p align="center">
  
![1](https://user-images.githubusercontent.com/77898496/214306140-21962c9b-ddfd-453e-9ede-2a9856250457.png)
    
![3](https://user-images.githubusercontent.com/77898496/214306180-4752edc0-8d16-4b3a-817c-ec8db6b4266b.png)
  
![4](https://user-images.githubusercontent.com/77898496/214306192-884dcd3d-28fd-456f-92cc-794d17929964.png)
  
![5](https://user-images.githubusercontent.com/77898496/214306206-dfcb4cf5-943d-497d-8c0d-09a975a7780a.png)
  
![6](https://user-images.githubusercontent.com/77898496/214306221-ec5810a5-f6b3-4c28-9793-1430a7566b59.png)
  
<p>

# IV. BONUS  : (Personnalisation du theme de la page de login keycloak)

![3](https://user-images.githubusercontent.com/77898496/209239041-9859be51-427a-4e2f-af2e-d99c8d6884fe.png)

## BONNE RECEPTION 😊 
