# eureka_discovery
#Création de l'annuaire Eureka Discrovery Service
  ## Pour Activer le service EUREKa il faut juste activer la notation @EnableEurekaServer comme suit 
 > ![image](https://user-images.githubusercontent.com/86606579/207097859-ac024b6d-6d75-429a-b8fb-0acfcf7e6f71.png)
  ## Dans le fichier Application.proporties il faut ajouter des configurations comme le port et des propreties il faut mettre false 
 > ![image](https://user-images.githubusercontent.com/86606579/207098422-d02db086-cafe-4288-a58e-6ab24cc9a1ce.png)
   ## après je lance le service EUREKA sur le port 8761 voilà le resultat qui s'affiche 
  > ![image](https://user-images.githubusercontent.com/86606579/207099395-0b1b073f-040b-40b9-854c-cc9a872dcb10.png)
   ## Après que j'ai activer spring.cloud.discovery.enabled=true et j'ai mis true au lieu de false dans toutes les micro services et j'ai rédemarer les applications         voilà le résulat qui s'affiche 
  > ![image](https://user-images.githubusercontent.com/86606579/207100105-da3546f7-b3f6-4e2f-afcb-29ec3bc93e41.png)

