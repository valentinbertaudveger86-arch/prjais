# CAHIERS DES CHARGES | SUPERVISION 🕵️‍♂️

> Projet de supervision pour un **Titre Pro Administrateur d'Infrastructures Securisées** | BERTAUD--VEGER Valentin 👨‍💻
---

## I.	Contexte & Problématique

L’infrastructure actuelle manque de visibilité et de centralisation. Une reprise progressive de l’administration de l’infrastructure est en cours, suite à l’arrivée récente d’un premier administrateur à plein temps.

De nombreux sujets ont été initiés par le passé sans être pleinement finalisés, ce qui rend l’état global de l’infrastructure difficile à appréhender. Par ailleurs, plusieurs prestataires externes interviennent sur différents périmètres, ce qui complexifie le suivi opérationnel et la gestion quotidienne.

Dans un contexte de reprise en interne des activités et de résiliation progressive de certains contrats de prestation, il devient nécessaire de disposer d’une solution de supervision centralisée.

À ce jour, l’absence de supervision globale entraîne une détection tardive des incidents, impactant la disponibilité des services et la réactivité des équipes. Les prestataires ne disposant pas non plus de dispositifs de supervision, des vérifications manuelles quotidiennes des services et des serveurs sont nécessaires, générant une perte de temps et un risque accru d’incidents non détectés.

---

## II.	Objectifs du projet


- Mettre en place une supervision centralisée.
- Améliorer la disponibilité des services.
- Anticiper les incidents.
- Intégrer des indicateurs de sécurité.

---

## III.  Périmètre d'intervention

- Hyperviseur avec une VM de supervision
- Tous les équipement réseaux pour pouvoir les superviser (Switch, pare-feu, VPN, FTTO, FTTH etc...)

> Le périmètre d'intervention dépendra de **la reprise progressive de l'infrastructure.** Actuellement géré par des prestataires, il est difficile de reprendre la main dessus **(21/01/2026 15:05).**

---

## III.  Nos besoins 

**3.1 Besoins de supervision**
  -  *Superviser la disponibilité* : état en temps réel de chaque serveur, VM et équipement réseau (UP/DOWN), avec historique des indisponibilités.
  -  *Superviser les performances* : CPU, RAM, stockage, bande passante, VPN, latence et temps de réponse des services critiques.
  -  *Générer des alertes automatiques* : e-mail avec seuils configurables et priorisation (critique / warning / info).
  -  *Centraliser les événements et logs* : collecte centralisée, corrélation d’événements, filtrage par type ou gravité.
  -  *Tableaux de bord et rapports* : visualisation synthétique, graphiques d’évolution, rapports périodiques automatisés.
  -  *Superviser les services applicatifs* : disponibilité et erreurs des services critiques (GeoHecras, ZWCad).
  -  *Automatisation des actions (optionnel)* : redémarrage de services/VM, scripts de remédiation.

**3.2 Besoins en cybersécurité**

-  Gestion fine des rôles et droits d’accès : opérateur, administrateur, lecture seule.
-  Journalisation complète : connexions, modifications de configuration, actions critiques.
-  Chiffrement des communications : TLS/SSL entre agents et serveur.
-  Authentification forte : MFA, intégration AD/LDAP.
-  Alertes de sécurité : détection et notification des accès non autorisés.
-  Conformité ANSSI : hardening des serveurs de supervision, segmentation réseau, limitation des ports.

**3.3 Besoins techniques**

-  Compatible Linux et Windows, agent et agentless selon équipements.
-  Interface web sécurisée et responsive.
-  Architecture évolutive pour l’ajout futur de serveurs et équipements.
-  Support des protocoles standards : SNMP, ICMP, SSH, API REST, WMI.
-  Capacité à gérer plusieurs devices sans dégradation.
-  Intégration avec les systèmes existants (AD/LDAP).
-  Sauvegarde/restauration de configuration et historiques.

> Tous ces besoins peuvent être modifier ou retirer lors de la phase de test. Et par la suite accepté par les parties prenantes.

---

## IV.  Contraintes 

Sur un pro

-  Budget limité : pas de gros investissement matériel ou logiciel.
-  Temps de mise en œuvre contraint : planification réaliste selon ton calendrier d’études et disponibilité des serveurs.
-  Complexité de l’infrastructure : plusieurs prestataires externes, équipements variés → choix d’une solution flexible.
-  Contrainte de sécurité : respecter les bonnes pratiques ANSSI et l’orientation cybersécurité.

---

## V.  Livrables attendus 💡 

-  Solution de supervision opérationnelle : serveur/VM configuré avec les agents et la collecte d’événements.
-  Tableaux de bord : visualisation de la disponibilité, performance, alertes, sécurité.
-  Procédures d’exploitation : comment surveiller, gérer les alertes, ajouter des équipements, sauvegarder/restaurer la supervision.
-  Dossier projet complet : cahier des charges, schémas, rapports, captures d’écran, justification des choix.

---
