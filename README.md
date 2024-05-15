# Activité Pratique 6 : Première Partie : GRPC - Client 

## Mise en œuvre de gRPC

### Modèle Unaire

Les RPC unaires sont le type le plus simple de RPC. Le client envoie une seule requête et reçoit une seule réponse.

### Modèle de Streaming Serveur

Le RPC de streaming serveur permet au serveur d'envoyer plusieurs réponses à une seule requête client.

### Modèle de Streaming Client

Le RPC de streaming client permet au client d'envoyer un flux de requêtes au serveur et de recevoir une seule réponse.

### Modèle de Streaming Bidirectionnel

Le RPC de streaming bidirectionnel permet au client et au serveur d'envoyer un flux de messages l'un à l'autre.
