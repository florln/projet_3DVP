## COMMENT EXECUTER LES TESTS:
* npm test # commande pour lancer les tests
* npm start # cammande pour démarrer le serveur de l'application 
* Server running at http://localhost:3000
## CONSTRUIRE L'IMAGE DOCKER ET DEPLOYER L'APPLICATION:
* docker build -t feux de signalisation .
  docker run -d -p 80:80 frux de signalisation
* application sera accessible à l'adresse http://localhost:80