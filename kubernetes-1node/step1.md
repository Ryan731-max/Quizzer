
Run `k get pod -A`{{exec}}
01. Dans le dossier root, Créer le dossier test_{votre-nom} "Exemple : test_charlie-ferreau" [Aucune aide disponible]
02. Créer le fichier docker-compose.yml [Aucune aide disponible]
03. Créer les dépendances nécessaires (dossiers de priorisation des configuration, comme configs, certs ou ssl) [Aucune aide disponible]
04. Modifier le fichier docker-compose.yml 
05. Mettez les lignes conventionnelles nécessaires au déploiement de docker-compose [Services, environment, ports, etc.]
06. Il vous faut impérativement créer un volume avant de déployer votre image
07. Dans votre énoncé ici présent, Vous avez 2 services dans un seul grand bloc. (web:, certbot:)
Remarques, vous pouvez également choisir de créer Certbot à l'extérieur des conteneurs comme toute application native.
