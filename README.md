# Java_Projet_4heures
Projet réalisé en cours pendant 4 heures durant ma 2ème année de licence.  
Etapes :  
1. Installer WAMP.  
2. Activer MySQL.  
3. Dans PHP My Admin Créer une base de données nommée "article"  
4. Dans cet base importer le ficher article.sql fourni  
5. Dans Eclipse (ou autre IDE) importer "mysql-connector-java-5.1.48.jar" qui se trouve dans le zip "mysql-connector-java-5.1.48"  
6. Penser à ajouter la bibliothèque mysql-connector-java-5.1.48.jar dans les bibliotheques du projet  
7. Dans le fichier MY_CONNECTION vous trouverez les informations suivantes : si votre User, Password... veuillez le mofifier dans ce fichier  
		mds.setServerName("localhost");  
		mds.setPortNumber(3306);  
		mds.setUser("root");  
		mds.setPassword("");  
		mds.setDatabaseName("article");  
