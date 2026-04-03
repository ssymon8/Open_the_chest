# Reconnaissance de Tâches Robotiques dans des Environnements Pilotés par Événements

Ce projet combine **l'apprentissage par renforcement (RL)** avec la **simulation robotique** pour développer un système capable de reconnaître des événements complexes et d'exécuter des actions manipulatrices avec un bras robotique KUKA.

##  Structure du Projet

```
Open_the_chest/
├── Open_The_Chests_Project.ipynb      # Notebook principal contenant tout le projet
├── colored_chest_kuka_env.py           # Environnement personnalisé KUKA en PyBullet
├── register_envs.py                    # Script d'enregistrement des environnements
├── model_baseline_ppo.pth              # Modèle KUKA entraîné (baseline)
├── model_baseline_ppo.zip              # Archive du modèle baseline
├── model_optimized_ppo.pth             # Modèle KUKA entraîné (optimisé)
├── model_task3_otc.zip                 # Modèle Open the Chests entraîné
├── kuka_episode.mp4                    # Vidéo de démonstration KUKA
├── task3_dual_agent_results.png        # Visualisation des résultats du système dual-agent
├── readme.md                           # Ce fichier
└── envR/                               # Environnement virtuel Python
```

##  Comment Exécuter le Code

###  Exécuter le Notebook

Le projet complet est contenu dans `Open_The_Chests_Project.ipynb`. 

