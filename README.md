# juste-acko-portofolio.github.io

# 🌐 Portfolio – Cybersécurité, Réseaux & Administration Système

Bienvenue sur mon portfolio professionnel.  
Ce site regroupe mes projets, études de cas et réalisations pratiques dans les domaines de la cybersécurité, des réseaux et de l’administration système.  
Il a été créé dans le cadre de ma recherche d’un **stage de fin d’études** afin de présenter concrètement mes compétences techniques.

---

## 👤 À propos de moi

Étudiant passionné par la cybersécurité et les systèmes réseau, je combine une formation académique solide avec des projets techniques pratiques que je réalise pour renforcer continuellement mes compétences.

🎯 **Objectif :** intégrer une équipe pour un stage de fin d’études où je pourrai contribuer à la sécurité et à l’optimisation d’infrastructures réelles.

---

## 🛡️ Compétences

### Cybersécurité / Cyberdéfense
Firewalling & filtrage : firewalls, ACL, politiques de filtrage  
IDS/IPS : détection d’intrusions, règles signatures, gestion des faux positifs  
Analyse réseau : Wireshark, inspection profonde, analyse de flux et anomalies  
Sécurisation des communications : VPN/IPSec, TLS  
Bonnes pratiques Linux & Windows  
Gestion d’incidents & SOC : niveau 1/2  
Veille & analyse de menaces : exploitation rapports CERT/ANSSI  

---

### IAM / Contrôle d’accès
AAA : Diameter, TACACS+, LDAP, Kerberos  
Modèles de droits & RBAC  
Gestion du cycle de vie des identités  
Certificats & authentification forte  
Comptes à privilèges (PAM)  
Concepts SSO, MFA, fédération  
Gouvernance des accès  
SELinux (principes, politiques de sécurité, troubleshooting)  

---

### Sécurité des SI
ISO 27001, EBIOS RM, ANSSI  
Analyse de vulnérabilités : Nessus, Nmap  
IPSec, VPN, firewalls, proxies  
SELinux : contexts, policies, MAC, analyse des AVC  
Rédaction de rapports sécurité & conformité  

---

### Systèmes & Réseaux
Linux (Ubuntu), Windows Server  
VLAN, DHCP, DNS, routage, Wireshark  
Virtualisation : VMware, VirtualBox  
Docker, Kubernetes (notions)  
Ansible : inventaires, rôles, playbooks  

---

### Analyse de données et développement
Analyse d'habilitations, détection d’anomalies  
Normalisation & qualité des données  
Tableaux de bord : Power BI, Tableau, Excel  
Python, Java, MySQL  
Scripts d’automatisation  

---

### Soft Skills
Vulgarisation technique, esprit d’analyse  
Présentation aux équipes techniques et métiers  
Gestion du stress & autonomie  
Coordination interservices, travail en équipe  

## 🧩 Projets principaux


### 🔸 1. Déploiement d’un IDS & simulation d’attaques (Suricata, Docker)
Mise en place d’un IDS Suricata dans un environnement containerisé avec création d’un laboratoire d’attaque contrôlé (Kali Linux → DVWA).  
Réalisation de scans automatisés (Nmap), attaques brute-force (Hydra) et exploitation de vulnérabilités (Metasploit).  
Analyse approfondie des logs pour améliorer les règles de détection et la précision des alertes.  
**Compétences :** Suricata, Docker, Nmap, Hydra, Metasploit, analyse de logs, sécurité réseau.  

---

### 🔸 2. Déploiement SIEM – Wazuh (manager + agents)
Installation du manager Wazuh et déploiement des agents Windows/Linux.  
Intégration avec OpenSearch/Kibana pour la centralisation des logs.  
Création de règles personnalisées, normalisation des événements et alertes sur IOC.  
Réalisation d’attaques simulées pour valider les détections et la corrélation d’événements.  
**Compétences :** Wazuh, OpenSearch, Linux, FIM, audit système, threat detection.  

---

### 🔸 3. Architecture IAM / AAA & sécurisation d’un réseau multi-site
Conception d’une architecture IAM complète : FreeDiameter + LDAP.  
Implémentation du RBAC, authentification forte via certificats (PKI interne), segmentation via VLAN.  
Sécurisation des communications (IPsec/TLS), documentation des modèles d’habilitation et audit de conformité.  
**Compétences :** IAM, AAA, RBAC, LDAP, FreeDiameter, PKI, VLAN, IPSec/TLS.  

---

### 🔸 4. Cybersécurité – HIDS & environnements conteneurisés
Déploiement d’hôtes vulnérables avec Podman (exploits : SQL Injection, Log4Shell).  
Intégration Wazuh HIDS pour la détection hôte : FIM, auditd, syscheck, log monitoring.  
Analyse de vulnérabilités via bases CVE intégrées et recommandations de remédiation.  
**Compétences :** Podman, Wazuh HIDS, CVE analysis, Linux security.  

---

### 🔸 5. Infrastructure as Code – Automatisation FortiGate (Ansible)
Automatisation complète du firewall FortiGate via API FortiOS + modules Ansible.  
Playbooks pour la gestion des interfaces (WAN, LAN, DMZ), création d’objets, VRF, VIP, politiques de sécurité et audit de conformité.  
Mises à jour automatisées et gestion centralisée des configurations.  
**Compétences :** Ansible, FortiGate, FortiOS API, IaC, réseaux, firewalling.  

### 🔸 6. Administration et gestion complète de GLPI (ITSM)
Installation et configuration complète de la plateforme GLPI pour la gestion des services IT.  
Mise en place de la base de données, optimisation des paramètres serveur et sécurisation de l’environnement.  
Configuration avancée : entités, profils, rôles, droits, flux ITSM, catalogue de services et formulaires d’assistance.  
Déploiement des plugins essentiels : inventory, dashboard, fusioninventory…  
Mise en place des SLA/OLA, automatisations, notifications et procédures d’exploitation.  
Rédaction de documentation technique structurée pour une prise en main opérationnelle.  
**Compétences :** GLPI, ITSM, SQL, workflows, documentation, gestion des services.  

---

### 🔸 7. Supervision réseau & ITSM : intégration GLPI + Zabbix
Installation et configuration d’un serveur Zabbix pour la supervision des équipements réseau, systèmes et services.  
Intégration complète GLPI–Zabbix : remontée automatique des alertes, incidents et inventaire dynamique.  
Création et optimisation de templates de supervision (réseau, serveurs, services critiques).  
Configuration des workflows GLPI pour générer automatiquement des tickets basés sur les alertes Zabbix.  
Déploiement de tableaux de bord centralisés pour le suivi en temps réel.  
Tests, validation fonctionnelle et documentation de l’architecture supervision + ITSM.  
**Compétences :** Zabbix, GLPI, supervision, monitoring réseau, tableaux de bord, workflows ITSM.  

---

## Contacts

🔗 **LinkedIn : https://www.linkedin.com/in/juste-fourier-acko-4a659017a/
📬 **Email :** ackojuste75@gmail.com

---

## 🚀 Objectif actuel

🔍 Je suis **à la recherche d’un stage de fin d’études** en cybersécurité, réseau ou administration système.  
N’hésitez pas à me contacter pour toute opportunité ou collaboration.

---

## 🏗️ Technologies utilisées pour ce portfolio
- GitHub Pages  
- HTML / CSS / JavaScript  
- Git / Versionning  

---

Merci pour votre visite !
