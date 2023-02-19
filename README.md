## SpringCloudStreamsKafka

#### 1°/ Démarrer Zookeeper

bin\windows\zookeeper-server-start.bat config/zookeeper.properties

#### 2°/ Démarrer Kafka-server

bin\windows\kafka-server-start.bat config/server.properties

#### 3°/ Tester avec Kefka-console-producer et kafka-console-consumer

![1](https://user-images.githubusercontent.com/102621314/213132569-138f4993-ff3b-4a93-919e-a1e38b5449b3.PNG)

#### 4°/  Avec Docker

 - Créer le fichier docker-compose.yml
 
 ![17](https://user-images.githubusercontent.com/102621314/213132659-a3df92be-fc6d-41af-b4d6-2ee3e2e3000f.PNG)

 - Démarrer les conteneurs docker : zookeeper et kafka-broker
 
 ![16](https://user-images.githubusercontent.com/102621314/213132714-18501a12-6432-4a09-b250-34d2b0aa1ead.PNG)

 - Tester avec Kafka-console-producer et kafka-console-consumer
 
 ![18](https://user-images.githubusercontent.com/102621314/213132789-0263f580-82fa-4c9c-bdcf-17656867de67.PNG)
 
 ![19](https://user-images.githubusercontent.com/102621314/213132791-13027c4e-c6bb-41ca-a012-13976e048c4a.PNG)
 
 ![20](https://user-images.githubusercontent.com/102621314/213132907-56c3d5da-d1bb-4dea-a20e-f7db5c9b8838.PNG)
 
 ![21](https://user-images.githubusercontent.com/102621314/213132964-24ded6f9-c459-4d73-b0ee-53b6b8832220.PNG)

#### 5°/ En Utilisant KAFKA et Stpring Cloud Streams, Créer :

- Un Service Producer KAFKA via un Rest Controler

 ![11](https://user-images.githubusercontent.com/102621314/213133098-5acc8d9f-47f9-4f0c-9e61-0161fb9209c6.PNG)
 
 ![2](https://user-images.githubusercontent.com/102621314/213133133-afbcbe88-7400-42d2-a8f7-b0105305d03e.PNG)

- Un Service Consumer KAFKA

 ![8](https://user-images.githubusercontent.com/102621314/213133235-e28c685b-be63-4e06-a568-4a298730b8b1.PNG)
  
 ![3](https://user-images.githubusercontent.com/102621314/213133281-2b63aa82-e3f5-4079-8425-ab6fba28346a.PNG)
 
 ![4](https://user-images.githubusercontent.com/102621314/213133352-aa83bd81-daa7-4bd3-86dc-fa82a3f66e03.PNG)
 
- Un Service Supplier KAFKA

 ![9](https://user-images.githubusercontent.com/102621314/213133420-d3e308da-9be0-4d71-b00f-759d3adcb878.PNG)
 
 ![5](https://user-images.githubusercontent.com/102621314/213133468-2570234f-ed38-40d3-95eb-fe3dd6fda01c.PNG)

- Un Service de Data Analytics Real Time Stream Processing avec Kaflka Streams

 ![10](https://user-images.githubusercontent.com/102621314/213133582-53b9135b-576b-44be-a719-af76ff3612f1.PNG)
 
 ![6](https://user-images.githubusercontent.com/102621314/213133631-46d4d7d1-d3f0-4e6a-85aa-18dd5b63a497.PNG)
 
 ![7](https://user-images.githubusercontent.com/102621314/213133633-91607c4c-da97-4a0a-a964-68c79e638b53.PNG)

 ![12](https://user-images.githubusercontent.com/102621314/213133690-a4ddd69a-57db-4cee-9f63-93b5feadb77c.PNG)

- Une application Web qui permet d'afficher les résultats du Stream Data Analytics en temps réel

 ![14](https://user-images.githubusercontent.com/102621314/213133798-df09c1c4-e27f-409e-bd93-28d69ae9c02d.PNG)
 
 ![13](https://user-images.githubusercontent.com/102621314/213133813-bebae0eb-a884-4867-b35d-40f490feefbe.PNG)

 ![15](https://user-images.githubusercontent.com/102621314/213133808-e1a44ddc-3b3b-475d-bcea-598b963a66a0.PNG)
