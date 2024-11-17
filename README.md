## Description du Projet  

Ce projet explore l'implémentation des ReplicaSets avec MongoDB pour garantir la haute disponibilité et la tolérance aux pannes des bases de données. Les étapes comprennent la configuration de plusieurs instances MongoDB, la gestion des élections de nœuds primaires, et la simulation de scénarios de panne.

### Principales Étapes Réalisées :  
1. Configuration de l'environnement MongoDB  
2. Initialisation du ReplicaSet avec un nœud primaire et des nœuds secondaires  
3. Ajout d'un arbitre pour la gestion des élections  
4. Simulation de pannes et tests de tolérance  
5. Validation des résultats de réplication et des restrictions d'écriture

### Environnement Utilisé  
- **MongoDB** pour la base de données distribuée  
- **MongoDB Shell** pour la configuration et la gestion des instances  

### Avantages des ReplicaSets :  
- Haute disponibilité des données  
- Mise à jour continue sans interruption  
- Résilience face aux défaillances de serveurs  
- Meilleure répartition des charges de lecture  
