<div align="center">

<img src="assets/photass.png" alt="M'BOH Mohamed" width="229"/>

# M'BOH Mohamed

**Sécurité réseau & systèmes · Blue Team · Détection & durcissement**

Licence 3 Informatique & Cybersécurité — Groupe ISM Dakar

![Fortinet NSE 1-3](https://img.shields.io/badge/Fortinet-NSE%201--3-EE3124)
![Cisco NetAcad](https://img.shields.io/badge/Cisco-NetAcad-1BA0D7)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE-ATT%26CK-005f87)
![Sigma](https://img.shields.io/badge/Sigma-YARA-444)

[LinkedIn](https://www.linkedin.com/in/m-boh-mohamed-343684330) · [Email](mailto:med.guest740@gmail.com) · [Rapports](reports/) · [Articles](#-articles)

</div>

---

## 🧭 Profil

Je conçois, configure et teste des infrastructures sécurisées en laboratoire : segmentation réseau et pare-feu (FortiGate, pfSense), annuaires Active Directory, durcissement Linux et conteneurs, ingénierie de détection (Sigma, YARA) et analyse de malware. Chaque travail est documenté dans un rapport avec preuves (captures, commandes, résultats) et limites assumées.

**Domaines de travail**
- Sécurité des réseaux : pare-feu NGFW, filtrage, NAT, segmentation
- Sécurité des systèmes : Active Directory, durcissement Linux, isolation et confinement
- Détection et réponse : MITRE ATT&CK, règles Sigma/YARA, chasse aux menaces, analyse de malware
- Automatisation et DevOps : CI/CD, supervision, Machine Learning appliqué à la détection

---

## 🎯 Motivation

Les cyberattaques se multiplient d'année en année, et l'Afrique n'y échappe pas. Selon INTERPOL, la cybercriminalité représente plus de 30 % des crimes déclarés en Afrique de l'Ouest et de l'Est, alors que seuls 30 % des pays africains disposent d'un système de signalement des incidents<sup>[1]</sup>. Les cibles sont des institutions dont dépendent les citoyens.

Protéger ces systèmes, c'est protéger la continuité des services et la confiance dans le numérique, donc en partie la souveraineté de nos États. Pour moi, ce n'est ni une simple envie ni une passion passagère : c'est un engagement.

---

## 🧰 Compétences

| Domaine | Outils et technologies |
|---|---|
| **Détection & réponse** | MITRE ATT&CK, Sigma, YARA, Hayabusa, Splunk, Auditd, Falco, MISP |
| **Analyse de malware** | Analyse statique et dynamique (ELF), INetSim, IOC, règles YARA |
| **Réseau & pare-feu** | FortiGate, pfSense, NAT/DNAT, filtrage, segmentation |
| **Systèmes & annuaires** | Active Directory (AD DS, DNS, GPO, FGPP), PowerShell, Windows Server 2022, Ubuntu Server |
| **Conteneurs & durcissement** | Docker, seccomp, capabilities, namespaces/cgroups, AppArmor, Trivy |
| **DevOps** | Git/GitHub, Jenkins, Docker, SonarQube, Prometheus, Grafana |
| **IA / Données** | Python, scikit-learn, Pandas, Prophet, Streamlit |
| **Virtualisation** | VMware Workstation Pro, WSL2 |

---

## 🏅 Certifications

| Certification | Organisme |
|---|---|
| Fortinet NSE 1, 2 et 3 | Fortinet |
| Cisco NetAcad | Cisco Networking Academy |

---

## 💼 Expérience

**Stage — Département Sécurité Informatique, Moov Mauritel** · juillet – septembre 2026
- Déploiement d'un pare-feu de nouvelle génération **FortiGate** et définition des politiques de sécurité
- Segmentation du réseau et intégration de postes clients (Windows 10, Ubuntu, Windows Server 2022)
- Mise en place d'un contrôleur de domaine **Active Directory**
- Environnement virtualisé VMware, encadré par le Chef de Service Sécurité Informatique (RSSI)

---

## 📁 Projets

### Détection, chasse aux menaces et analyse de malware

| Projet | Contenu | Outils | Rapport |
|---|---|---|---|
| **Lab — Analyse de logiciel malveillant** | Analyse statique et dynamique d'un échantillon ELF en laboratoire isolé : dépôt de fichier, balise C2, persistance `@reboot`, processus résident. Production d'IOC, cartographie ATT&CK et règle YARA testée. | YARA, INetSim, ATT&CK | [PDF](reports/Lab_Analyse_Malware.pdf) |
| **Lab — Ingénierie de détection et chasse aux menaces** | Cycle complet : cartographie ATT&CK, règles Sigma (création de compte Linux, PowerShell encodé), règles YARA fichier + mémoire (faux positif corrigé en V2), chasse (3 artefacts : cron, SUID, compte backdoor), IOC. | Sigma, YARA, Hayabusa, Auditd, MISP | [PDF](reports/Lab_Ingenierie_de_detection.pdf) |
| **Détection d'intrusions par Machine Learning** *(projet de groupe)* | Comparaison de 5 modèles de classification sur un jeu de données d'intrusions : EDA, prétraitement, GridSearch, validation croisée. **Meilleur modèle : Random Forest, F1 = 0,96.** | Python, scikit-learn | [PDF](reports/ML_Detection_Intrusions.pdf) |

### Sécurité des systèmes et des réseaux

| Projet | Contenu | Outils | Rapport |
|---|---|---|---|
| **Lab — Isolation et confinement avancés** | Confinement de services conteneurisés : capabilities, filtrage seccomp, namespaces/cgroups, AppArmor, durcissement Docker, scan d'images, démonstration défensive d'évasion, détection à l'exécution. | Docker, seccomp, AppArmor, Trivy, Falco | [PDF](reports/Lab_Isolation_Confinement.pdf) |
| **Active Directory sécurisé et administré en PowerShell** | Domaine `MedAD.local` : OU, groupes (RBAC), politique de mot de passe granulaire (FGPP), audit par GPO, administration et audit exclusivement en PowerShell. | Windows Server 2022, PowerShell, GPO | [PDF](reports/Active_Directory_PowerShell.pdf) |
| **Filtrage avancé et NAT sur pfSense** | Alias, règles LAN ordonnées avec deny-all explicite et journalisation, suppression de la règle « allow all », Outbound NAT (Hybrid) et Port Forward vers un serveur web interne. | pfSense | [PDF](reports/pfSense_Filtrage_NAT.pdf) |
| **Architecture réseau sécurisée et segmentée** *(stage Moov Mauritel)* | FortiGate, politiques de sécurité, postes clients, contrôleur de domaine Active Directory. | FortiGate, AD DS, VMware | Sur demande |

### DevOps et développement

| Projet | Contenu | Outils | Rapport |
|---|---|---|---|
| **Pipeline DevOps CI/CD complet** | Chaîne de bout en bout : GitHub → Jenkins (pipeline déclaratif) → Docker/DockerHub, analyse qualité et supervision. | Jenkins, Docker, SonarQube, Prometheus, Grafana | [PDF](reports/DevOps_Pipeline_CICD.pdf) |
| **Plateforme de comptabilité automatisée pour PME** *(hackathon, volet cybersécurité)* | Plateforme open-source modulaire (OCR + Random Forest, rapprochement bancaire, budget prévisionnel, états OHADA). Mon volet : sécurité et chiffrement des données financières. | Python, Streamlit, Fernet, Prophet | Sur demande |

---

## ✍️ Articles

| Date | Titre | Lien |
|---|---|---|
| — | *Titre de l'article* | [Lire](articles/nom-article.md) |

---

## 🗂️ Organisation du dépôt

```
├── README.md
├── assets/      # photo et visuels
├── reports/     # rapports complets des labs et projets (PDF)
└── articles/    # articles et notes techniques
```

---

<sub>[1] INTERPOL, *Africa Cyberthreat Assessment Report 2025*, juin 2025 — [interpol.int](https://www.interpol.int/News-and-Events/News/2025/New-INTERPOL-report-warns-of-sharp-rise-in-African-cybercrime)</sub>

<div align="center"><sub>Les rapports sont publiés à des fins pédagogiques. Les environnements décrits sont des laboratoires isolés.</sub></div>
