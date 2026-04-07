# NTL-SYSTOOLBOX-MSPR2
Ce projet s'inscrit dans le cadre de la modernisation de l'infrastructure de Nord Transit Logistics, une PME de logistique basée dans les Hauts-de-France. L'entreprise fait face à une forte croissance et doit sécuriser son Système d'Information pour garantir la continuité de ses opérations critiques.
Durée de préparation : 19 heures.

**Objectif :** Proposer et maquetter une architecture cible résiliente, hybride (On-premise & Azure) et sécurisée.

# Enjeux Techniques & Objectifs

L'équipe doit répondre aux problématiques suivantes détaillées dans le cahier des charges :

- **Réseau & Sécurité :** Homogénéisation du parc de pare-feu, mise en place d'un VPN site-à-site centralisé et segmentation par VLAN (Voix, Data, Management).

- **Haute Disponibilité (HA) :** Remplacement de l'hôte unique Dell PowerEdge par un cluster haute disponibilité avec stockage redondé pour supprimer les points de défaillance.

- **Continuité d'Activité (PCA/PRA) :** Définition des objectifs RTO/RPO pour l'Active Directory et le système de gestion d'entrepôt (WMS).

- **Cloud Hybride :** Déploiement d'une Landing Zone Azure connectée au siège par tunnel sécurisé pour l'externalisation des sauvegardes et la redondance des contrôleurs de domaine.

- **Qualité de Service (QoS) :** Priorisation de la Voix sur IP (ToIP) pour garantir la fluidité des communications sur les sites distants.

# Contenu du Repository

Ce dépôt GitHub centralise l'ensemble des preuves techniques et livrables du projet :

``/Architecture`` : Plan d'adressage IP, schémas réseau et tableaux de segmentation.

``/Configs`` : Fichiers de configuration des équipements (Firewalls, Switchs, VPN).

``/Livrables`` : Document d'Architecture Technique (DAT), Stratégie de migration et Note de recommandation WMS.

``/Exploitation`` : Guide de dépannage ToIP (N1/N2) et tableau de supervision.

``/POC`` : Rapports de tests (Failover AD, mesure de QoS, tunnel Azure).
