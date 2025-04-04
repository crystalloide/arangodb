<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://user-images.githubusercontent.com/7819991/218699214-264942f9-b020-4f50-b1a6-3363cdc0ddc9.svg" width="638" height="105">
  <source media="(prefers-color-scheme: light)" srcset="https://user-images.githubusercontent.com/7819991/218699215-b9b4a465-45f8-4db9-b5a4-ba912541e017.svg" width="638" height="105">
  <img alt="Two stylized avocado halves and the product name." src="https://user-images.githubusercontent.com/7819991/218697980-26ffd7af-cf29-4365-8a5d-504b850fc6b1.png" width="638" height="105">
</picture>

ArangoDB :
========

ArangoDB est un système de base de données graphique évolutif permettant de valoriser plus rapidement les données connectées. 

Graphes natifs, moteur de recherche intégré et prise en charge JSON via un langage de requête unique. ArangoDB fonctionne sur site, dans le cloud, partout.

ArangoDB Cloud Service :
----------------------

La plateforme ArangoGraph Insights  [ArangoGraph Insights Platform](https://cloud.arangodb.com/home) est le moyen le plus simple d'exécuter ArangoDB. 

Elle permet de créer facilement des déploiements sur tous les principaux fournisseurs de cloud dans de nombreuses régions.

Pour démarrer :
---------------

- [ArangoDB University](https://university.arangodb.com/)
- [Free Udemy Course](https://www.udemy.com/course/getting-started-with-arangodb)
- [Training Center](https://www.arangodb.com/learn/)
- [Documentation](https://docs.arangodb.com/)

Pour les plus impatients :

- Test gratuit d'ArangoDB dans le cloud avec [ArangoGraph](https://cloud.arangodb.com/home)

- Alternative en local : [Télécharger ici](https://www.arangodb.com/download) et installer ArangoDB.
   Démarrez le serveur avec 'arangod' si le programme d'installation ne l'a pas déjà fait.

  Ou démarrez ArangoDB dans un conteneur Docker : 

      docker run -e ARANGO_ROOT_PASSWORD=test123 -p 8529:8529 -d arangodb

  L'accès UI se fait ensuite avec un navigateur sur l'URL `http://127.0.0.1:8529/`

Principales caractéristiques d'ArangoDB :
------------------------

**Native Graph** - Stockez à la fois les données et les relations, pour des requêtes plus rapides, même avec plusieurs niveaux de jointures et des informations plus approfondies qui ne sont tout simplement pas possibles avec les systèmes de bases de données relationnelles et documentaires traditionnels.

**Document Store** - Chaque nœud de votre graphique est un document JSON : flexible, extensible et facilement importé à partir de votre base de données de documents existante.

**ArangoSearch** - Moteur d'indexation, de recherche de texte et de classement multiplateforme intégré nativement pour la recherche d'informations, optimisé pour la vitesse et la mémoire.

ArangoDB est disponible dans une édition communautaire gratuite et open source **Community Edition**, ainsi que dans une édition d'entreprise commerciale avec des fonctionnalités supplémentaires **Enterprise Edition**

### Fonctionnalités de l'édition communautaire

- **Horizontal scalability**: Évolutivité horizontale : répartissez vos données de manière transparente sur plusieurs machines.
- **High availability** and **resilience**: Haute disponibilité et résilience : répliquez les données sur plusieurs nœuds de cluster, avec basculement automatique.
- **Flexible data modeling**: Modélisation de données flexible : modélisez vos données sous forme de combinaison de paires clé-valeur, de documents et de graphiques selon vos besoins pour votre application.
- Work **schema-free** or use **schema validation** for data consistency. Travaillez sans schéma ou utilisez la validation de schéma pour la cohérence des données. Stockez tout type de données : date/heure, données géospatiales, texte, imbriquées.
- **Powerful query language** (_AQL_) Langage de requête puissant ( AQL ) pour récupérer et modifier des données - des opérations CRUD simples, en passant par des filtres et des agrégations complexes, jusqu'aux jointures, aux graphiques et à la recherche en texte intégral classée.
- **Transactions**: exécutez des requêtes sur plusieurs documents ou collections avec une cohérence et une isolation transactionnelles facultatives..
- **Data-centric microservices**: Microservices centrés sur les données : unifiez votre logique de stockage de données, réduisez la surcharge du réseau et sécurisez les données sensibles avec le framework JavaScript ArangoDB Foxx .
- **Fast access to your data**: Accès rapide à vos données : Affinez vos requêtes grâce à différents types d'index pour des performances optimales. ArangoDB est écrit en C++ et peut gérer efficacement des ensembles de données très volumineux.
- Easy to use **web interface** and **command-line tools** for interaction with the server. Interface Web facile à utiliser et outils de ligne de commande pour l'interaction avec le serveur.

### Fonctionnalités de l'édition Entreprise :

Concentrez-vous sur la résolution des problèmes d'entreprise pour les charges de travail critiques grâce à des données graphiques sécurisées. 

L'édition Entreprise reprend toutes les fonctionnalités de l'édition Communauté et offre des fonctionnalités supplémentaires en matière de performances, de conformité et de sécurité, ainsi que des capacités de requêtes étendues.

- Smartly shard and replicate graphs and datasets with features like  **EnterpriseGraphs**, **SmartGraphs**, and **SmartJoins** for lightning fast query execution. Divisez et répliquez intelligemment des graphiques et des ensembles de données avec des fonctionnalités telles que EnterpriseGraphs , SmartGraphs et SmartJoins pour une exécution de requêtes ultra-rapide.
- Combine the performance of a single server with the resilience of a cluster setup using **OneShard** deployments. Combinez les performances d’un serveur unique avec la résilience d’une configuration en cluster à l’aide des déploiements OneShard .
- Increase fault tolerance with **Datacenter-to-Datacenter Replication** and create incremental **Hot Backups** without downtime. Augmentez la tolérance aux pannes grâce à la réplication de Datacenter à Datacenter et créez des sauvegardes à chaud incrémentielles sans temps d'arrêt.
- Enable highly secure work with **Encryption 360**, enhanced **Data Masking**, and detailed **Auditing**. Activez un travail hautement sécurisé avec Encryption 360 , le masquage des données amélioré et l'audit détaillé .
- Perform **parallel graph traversals**. Effectuer des parcours de graphes parallèles .
- Use ArangoSearch **search highlighting** and **nested search** for advanced information retrieval. Utilisez la mise en évidence de la recherche et la recherche imbriquée d'ArangoSearch pour une recherche d'informations avancée.

Dernière Version disponible ici :
--------------

Les packages pour toutes les plates-formes prises en charge peuvent être téléchargés ici :
<https://www.arangodb.com/download/>.

Pour connaître les nouveautés d'ArangoDB, consultez les notes de publication ici : 
[Documentation](https://docs.arangodb.com/).

Pour rentrer en contact :
---------------

- Veuillez utiliser GitHub pour les demandes de fonctionnalités et les rapports de bogues :
  [https://github.com/arangodb/arangodb/issues](https://github.com/arangodb/arangodb/issues)

- Pour posez vos questions sur AQL, les scénarios d'utilisation, etc. sur StackOverflow :
  [https://stackoverflow.com/questions/tagged/arangodb](https://stackoverflow.com/questions/tagged/arangodb)

- Discutez avec la communauté et les développeurs sur Slack : 
  [https://arangodb-community.slack.com/](https://arangodb-community.slack.com/)

- Apprenez-en plus sur ArangoDB avec notre chaîne YouTube : 
  [https://www.youtube.com/@ArangoDB](https://www.youtube.com/@ArangoDB)

- Suivez-nous sur X pour rester à jour :
  [https://twitter.com/arangodb](https://twitter.com/arangodb)

- En savoir plus sur notre communauté : [https://www.arangodb.com/community](https://www.arangodb.com/community/)



______________________________________________________________________________________________________________
______________________________________________________________________________________________________________
______________________________________________________________________________________________________________


### Pour tester rapidement ArangoDB dans un environnement virtualisé "Gitpod"

Notre environnement de démonstration contient 1 noeud pour le momentt : 


#### Rappel pour retrouver les environnements éventuellement précédemment instanciés dans Gitpod : [ https://gitpod.io/workspaces ](https://gitpod.io/workspaces)

Nous allons déployer un conteneur docker ArangoDB sur un environnement virtuel accessible à partir d'un simple navigateur web, à des fins de développement et de formation. 

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/crystalloide/arangodb
)

#### 1°) On lance ArangoDB dans un conteneur Docker : 

      docker run -e ARANGO_ROOT_PASSWORD=test123 -p 8529:8529 -d arangodb

  L'accès UI se fait ensuite avec un navigateur sur l'URL `http://127.0.0.1:8529/`

#### cet URL est à adapter en fonction du nom de l'espace Gitpod instancié : 

####	2°) Pour lister l'image récupérée  :

    docker images

#### 3°) Attendre quelques minutes que les conteneurs démarrent

#### 4°) Affichage des conteneurs et vérification qu'ils sont bien en cours d'exécution : 

    docker ps -a 

#### bon test :-)

______________________________________________________________________________________________________________
______________________________________________________________________________________________________________
______________________________________________________________________________________________________________

