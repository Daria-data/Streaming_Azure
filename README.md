# Streaming_Azure
## Traitement des données en streaming avec Kafka et Databricks


Ces notebooks contiennent des exercices sur le traitement, le stockage et la transformation de données en streaming. Différentes approches ont été testées.

Suite à des problèmes de connexion entre Databricks et Event Hub, ainsi qu’à des difficultés d’installation de bibliothèques sur le cluster, j’ai utilisé l’API Kafka pour lire le flux de données Event Hub, où j’ai envoyé des données de taxis new-yorkais.

L’architecture mise en place :

Bronze : Stockage brut des messages Kafka.
Silver : Nettoyage et transformation des données.
Gold : Agrégation et analyse des courses de taxi.
