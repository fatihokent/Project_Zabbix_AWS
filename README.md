# Project_Zabbix_AWS

Auteur : fati
Encadrant : Prof. Azeddine KHIAT
Année universitaire : 2025/2026

Le but de ce projet est de configurer une infrastructure de monitoring centralisée sur AWS avec Zabbix pour surveiller un parc hybride (Linux & Windows).

📁 Structure du dépôt
docker-compose/ : Fichiers de configuration (docker-compose, agents Zabbix)
Rapport complet : sous format PDF
🔧 Architecture déployée
Réseau : 1 VPC avec sous-réseau public
Sécurité : Security Group avec ports 80,443,10050,10051,22,3389
Instances EC2 :
Serveur Zabbix : t3.large Ubuntu + Docker
Client Linux : t3.medium Ubuntu
Client Windows : t3.large Windows Server
