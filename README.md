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
  - lancement des serveurs : Eureka discovery -> gateway puis inventory, customer puis kafka-service pour cloturer avec le billing service <br>
  - D:\5IIR\J2EE\TPS\TP5\kafka_2.13-3.3.1\bin>``start windows\zookeeper-server-start.bat ../config/zookeeper.properties``
  - D:\5IIR\J2EE\TPS\TP5\kafka_2.13-3.3.1\bin>``start windows\kafka-server-start.bat ../config/server.properties``

# III- CAPTURES DE L'EXECUTION
<p align="center">
  
![1](https://user-images.githubusercontent.com/77898496/214628076-7e8ab0b2-944e-487d-a889-c2656167a5fc.png)

![2](https://user-images.githubusercontent.com/77898496/214628498-81774590-5f1d-4318-aece-09dc70f04c2c.png)

![3](https://user-images.githubusercontent.com/77898496/214628654-7b9710d9-ff7f-4310-acce-2fe9d85b347c.png)

### les données ont été ajouté apres avoir été consommé du topic R1 de kafka

![4](https://user-images.githubusercontent.com/77898496/214628717-61b44ed2-9b40-4411-8bbd-0283da6612e8.png)

![5](https://user-images.githubusercontent.com/77898496/214628751-5825cb76-bfa9-42fa-a7ef-472ec6dcd7c5.png)
### visualisation des données des factures produites dans le topic R1 et qui ont été consommé par le billing service 
D:\5IIR\J2EE\TPS\TP5\kafka_2.13-3.3.1\bin>``start windows\kafka-console-producer.bat --broker-list localhost:9092 --topic R1``

<p>

### j'ai une erreur `` data-analytics-service `` : `` can't deserialize data [[105, 109, 97, 110, 97]] from topic [r1] `` <br>
# V. DEPLOIMENT SUR DOCKER :
  
![Capture d’écran 2023-01-25 190700](https://user-images.githubusercontent.com/77898496/214646695-870c1d58-2c78-4f15-9dbb-ca608e4073c8.png)
  
![Capture d’écran 2023-01-25 190938](https://user-images.githubusercontent.com/77898496/214647104-95bd16a1-8f0c-4851-8258-2fe9d886b49e.png)

# IV. BONUS  : (Personnalisation du theme de la page de login keycloak) <br>

![3](https://user-images.githubusercontent.com/77898496/209239041-9859be51-427a-4e2f-af2e-d99c8d6884fe.png)

# V. Taches : 

- [x] Customer Service
- [x] Inventory Service
- [x] Gateway Service
- [x] Eureka Discovery
- [x] Billing Service
- [x] Angular Service
- [x] Securiser Services Avec Keycloak
- [x] Intégration du broker kafka
- [x] Micro-service producer facture
- [x] Consommer factures du Topic kafka - billing service
- [ ] Data-Analytics-Service [ erreur ]
- [ ] Affichage courbe
- [x] Deploiment Kafka
  
## BONNE RECEPTION 😊 :tada:
