# Validation projet Supervision

---

## Administrer et sécuriser les infrastructures

| **Compétence** | **Contexte / Besoin** | **Actions prévues dans le projet** | **Moyen envisagés** | **Livrables attendus** |
| --- | --- | --- | --- | --- |
| **Appliquer les bonnes pratiques d'administration** | Absence de visibilité sur l'état de l'infrastructure et détection tardive des incidents | Définir des procédures de supervision, d'alerte et de réaction aux incidents. Mettre en place des indicateurs de disponibilité et de performance | Outil de supervision, procédures documentées, seuils d'alerte | Procédures d'exploitation, seuils d'alertes, tableaux de bord |
| **Administrer et sécuriser les infrastructures réseaux** | Manque de supervision des équipements réseau et des performances | Superviser la disponibilité, la latence et les interfaces réseau afin d'anticiper les incidents | Supervision ICMP, surveillance interfaces, alertes | Règles de supervision réseau, dashboards |
| **Administrer et sécuriser les infrastructures systèmes** | Risque d'arrêt de services critiques non détecté | Superviser les serveurs Windows/Linux, les services critiques et l'utilisation des ressources | Agents de supervision, logs systèmes | Alertes systèmes, documentation |
| **Administrer et sécuriser les infrastructures virtualisées** | Manque de visibilité sur l'état des hyperviseurs et VM | Mettre en place des indicateurs de supervision des hôtes et machines virtuelles | Outil de supervision virtualisation | Tableaux de bord virtualisation |

---

- Appliquer les bonnes pratiques dans l'administration des infrastructures

Dans le cadre du projet de supervision, je mettrai en œuvre les bonnes pratiques d'administration des infrastructures en définissant des procédures de supervision, d'alerte et de réaction aux incidents.  
Le projet intégrera la planification des tâches d'exploitation telles que la surveillance de la disponibilité des services, des ressources systèmes et des sauvegardes.  
Les actions réalisées respecteront les recommandations de sécurité (ANSSI) et les principes de maintien en condition opérationnelle.  
Les livrables comprendront la documentation des procédures, les seuils d'alertes et les tableaux de bord de supervision.

- Administrer et sécuriser les infrastructures réseaux

Le projet de supervision permettra d'administrer et de sécuriser les infrastructures réseaux par la surveillance de la disponibilité, des performances et des flux réseau.  
Je mettrai en place des contrôles sur les équipements réseau (commutateurs, routeurs, pare-feu) afin de détecter les anomalies telles que les coupures, la saturation ou les latences.  
Cette supervision contribuera à l'amélioration de la sécurité et de la disponibilité des services réseau.  
Les livrables seront des règles de supervision réseau, des alertes et des tableaux de bord dédiés.

- Administrer et sécuriser les infrastructures systèmes

Dans le cadre du projet, j'administrerai et sécuriserai les infrastructures systèmes en supervisant les serveurs Windows et Linux ainsi que les services critiques.  
La supervision portera sur l'état des services, l'utilisation des ressources (CPU, mémoire, espace disque) et les événements systèmes.  
Cette démarche permettra d'anticiper les incidents et d'assurer la continuité de service.  
Les livrables incluront la configuration des agents de supervision, les alertes systèmes et la documentation associée.

- Administrer et sécuriser les infrastructures virtualisées

Le projet de supervision inclura l'administration et la sécurisation des infrastructures virtualisées par la surveillance des hyperviseurs et des machines virtuelles.  
Je mettrai en place des indicateurs permettant de contrôler l'état des hôtes, la consommation des ressources et la disponibilité des machines virtuelles.  
Cette supervision contribuera à optimiser l'utilisation des ressources et à détecter rapidement les incidents.  
Les livrables comprendront des tableaux de bord dédiés à l'environnement virtualisé.

---

- ## Concevoir et mettre en œuvre une solution en réponse à un besoin d'évolution

| **Compétence** | **Contexte / Besoin** | **Actions prévues dans le projet** | **Moyen envisagés** | **Livrables attendus** |
| --- | --- | --- | --- | --- |
| **Concevoir une solution technique** | Besoin d'une supervision centralisée et évolutive | Analyse du besoin, comparaison de solutions, choix argumenté | Étude comparative, environnement de test | Analyse du besoin, proposition technique |
| **Mettre en production une évolution** | Nécessité d'intégrer la solution sans impacter la production | Installation, configuration, tests et validation | Serveur de supervision, procédures | Procédures d'installation, tests |
| **Mettre en œuvre et optimiser la supervision** | Besoin d'indicateurs pertinents et fiables | Création de tableaux de bord, alertes et optimisation des seuils | Dashboards, indicateurs SLA | Tableaux de bord, règles d'alertes |

---

- Concevoir une solution technique répondant à des besoins d'évolution de l'infrastructure

Le projet vise à répondre à un besoin d'évolution de l'infrastructure par la mise en place d'une solution de supervision centralisée.  
J'analyserai le besoin, les contraintes techniques et de sécurité, et comparerai plusieurs solutions de supervision afin de proposer un choix argumenté.  
Un environnement de test sera prévu pour valider la solution avant sa mise en production.  
Les livrables incluront l'analyse du besoin, la comparaison des solutions et la proposition technique.

- Mettre en production des évolutions de l'infrastructure

Dans le cadre du projet, je planifierai et mettrai en production la solution de supervision retenue.  
Cette étape comprendra l'installation, la configuration, les tests fonctionnels et la validation des alertes.  
La mise en production sera accompagnée de la rédaction de la documentation d'exploitation et du transfert de compétences.  
Les livrables comprendront les procédures d'installation, de tests et d'exploitation.

- Mettre en œuvre et optimiser la supervision des infrastructures

Le projet consistera à mettre en œuvre et optimiser la supervision des infrastructures en définissant des indicateurs pertinents de performance, de disponibilité et de sécurité.  
Je configurerai des tableaux de bord et des alertes adaptées aux niveaux de service attendus.  
Une phase d'optimisation permettra d'ajuster les seuils afin de limiter les faux positifs et améliorer l'efficacité du dispositif.  
Les livrables seront les tableaux de bord, les règles d'alertes et les indicateurs SLA.

---

- ## Participer à la gestion de la cybersécurité

| **Compétence** | **Contexte / Besoin** | **Actions prévues dans le projet** | **Moyen envisagés** | **Livrables attendus** |
| --- | --- | --- | --- | --- |
| **Mesurer et analyser le niveau de sécurité** | Manque de visibilité sur les événements de sécurité | Superviser les logs et événements de sécurité | Logs systèmes, alertes | Règles de détection |
| **Participer à la mise en œuvre de la PSSI** | Nécessité d'appliquer la politique de sécurité | Intégrer des règles de supervision conformes à la PSSI | Procédures sécurité | Procédures documentées |
| **Détection et traitement des incidents** | Besoin de réactivité face aux incidents | Définir un processus de gestion des incidents | Alertes, procédures | Procédures + REX |

---

- Participer à la mesure et à l'analyse du niveau de sécurité de l'infrastructure

Le projet de supervision intégrera des mécanismes permettant de mesurer et d'analyser le niveau de sécurité de l'infrastructure.  
Je mettrai en place la surveillance des événements de sécurité et des journaux systèmes afin de détecter les comportements anormaux.  
Cette analyse contribuera à l'identification des vulnérabilités et des risques.  
Les livrables comprendront les règles de détection et les rapports d'événements.

- Participer à l'élaboration et à la mise en œuvre de la politique de sécurité

Dans le cadre du projet, je participerai à l'application de la politique de sécurité du système d'information en intégrant des règles de supervision conformes aux exigences de sécurité.  
Les procédures de réaction aux incidents seront définies et documentées.  
Les livrables incluront des procédures de sécurité et des règles de supervision alignées avec la PSSI.

- Participer à la détection et au traitement des incidents de sécurité

Le dispositif de supervision permettra de détecter les incidents de sécurité à partir des alertes générées.  
Je définirai les actions à mener en cas d'incident, depuis l'analyse jusqu'à la résolution et au retour d'expérience.  
Cette démarche permettra d'améliorer la réactivité et la résilience de l'infrastructure.  
Les livrables comprendront les procédures de gestion des incidents et les rapports de traitement.
