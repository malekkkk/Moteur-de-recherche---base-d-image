##################################################################################################################################################################
																				 #
Notez bien il faut installer le gestionnaire de paquets "yarn" ou lieu de "npm" car il est plus rapide !                                                         #
																				 #
******************************************************************************************************************************************************************

1) installer elasticSearch et logstash	

2) lancer elasticSearch et logstash

3) consulter Cr�ation_de_l_index_1.PNG pour cr�er l'index flickrphotos ( utiliser le fichier flickrphtos_mapping.txt pour le mapping ) 

4) consulter Importer_les_donn�es_avec_logstash.PNG pour importer les donn�es qui se trouve dans photo_metadata_ex.csv														 #
																				 #
5) ex�cuter le fichier "server�js" pour lancer le serveur � l'aide de commandes : 									 #
																				 #
	"node ./VueElasticNode-master/server/server.js"														 #
																				 #
3) D�placez sous le r�pertoire "VueElasticNode-master" et tapez la commande suivante pour lancer l'application "c�t� client" :					 #
																				 #
	"yarn serve"																		 #
																				 #
##################################################################################################################################################################