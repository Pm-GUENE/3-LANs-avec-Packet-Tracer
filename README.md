#  3-LANs-sur-Packet-Tracer
Configuration de 3 LANs avec services DHCP/DNS, Web et Messagerie sur Packet Tracer

![3LANs](https://github.com/user-attachments/assets/6fdf70c5-c39e-4284-b747-862c49e3efd8)


Objectif : Configurer un réseau local avec trois LANs distincts pour isoler les services et le trafic réseau. Chaque LAN héberge un serveur dédié pour différents services :

LAN1 : Serveur DHCP/DNS pour gérer l'adressage IP dynamique et la résolution DNS.
LAN2 : Serveur web pour héberger des pages web accessibles aux autres VLANs.
LAN3 : Serveur de messagerie pour gérer l'envoi et la réception des emails.

Après l’ouverture d’un fichier sauvegardé dans Packet Tracer, il est normal de devoir patienter quelques secondes (environ 10 à 30 secondes) pour que le serveur DHCP puisse reprendre ses activités et attribuer des adresses IP aux clients. Cela est dû à la manière dont Packet Tracer initialise les services réseau après le chargement du projet.

Pourquoi ce délai ?
	1.	Initialisation des services : Packet Tracer recharge les configurations et redémarre les services (comme DHCP, DNS, etc.) après l’ouverture d’un fichier sauvegardé.
	2.	Processus DHCP : Une fois le fichier ouvert, les clients envoient une nouvelle requête DHCP pour obtenir ou renouveler leurs adresses.

Comment gérer cela ?
•	Patientez naturellement : Les adresses IP seront attribuées automatiquement dans un délai court.
•	Forcer la requête DHCP (sur un client) :
    	1.	Allez sur un PC dans Desktop > IP Configuration.
    	2.	Cliquez sur Static puis repassez sur DHCP pour relancer immédiatement la requête.
