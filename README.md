<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1220,100:0077b6&height=200&section=header&text=Mickael&fontSize=62&fontColor=ffffff&fontAlignY=38&desc=Cybers%C3%A9curit%C3%A9%20%7C%20Triage%20SOC%20%7C%20Audit%20automatis%C3%A9&descAlignY=60&descSize=18" alt="Mickael, cybersécurité, triage SOC, audit automatisé" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=18&pause=1200&color=00B4D8&center=true&vCenter=true&width=640&lines=Admin+r%C3%A9seau+devenu+analyste+SOC;Logs+%E2%86%92+MITRE+ATT%26CK+%E2%86%92+D3FEND;Audit+de+s%C3%A9curit%C3%A9+automatis%C3%A9;Je+construis+mes+outils+pour+pratiquer" alt="Admin réseau devenu analyste SOC" />

<br/>

[![TryHackMe](https://img.shields.io/badge/TryHackMe-Mon%20profil-212C42?style=for-the-badge&logo=tryhackme&logoColor=white)](https://tryhackme.com/p/BlueLight)

**Menace** &nbsp;
![MITRE ATT&CK](https://img.shields.io/badge/MITRE-ATT%26CK-D32F2F?style=flat-square)
![MITRE ATLAS](https://img.shields.io/badge/MITRE-ATLAS-F57C00?style=flat-square)

**Défense** &nbsp;
![MITRE D3FEND](https://img.shields.io/badge/MITRE-D3FEND-0077B6?style=flat-square)
![Sigma](https://img.shields.io/badge/Sigma-rules-00B4D8?style=flat-square)

**Conformité** &nbsp;
![ISO 27001](https://img.shields.io/badge/ISO-27001-37474F?style=flat-square)
![NIS 2](https://img.shields.io/badge/NIS-2-37474F?style=flat-square)
![DORA](https://img.shields.io/badge/DORA-compliance-37474F?style=flat-square)

**Outils** &nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

</div>

---

## 👋 À propos

Je viens de l'administration réseau (environ 7 ans comme responsable informatique dans quatre établissements scolaires) et je me spécialise en cybersécurité défensive, avec pour objectif de devenir **analyste SOC**.

J'apprends en construisant : chaque outil ci-dessous répond à un besoin concret du métier.

---

## 🛠️ Projets

<table>
<tr>
<td width="50%" valign="top">

### 🗺️ [Cartographe ATT&CK](https://github.com/Mickaelb06/cartographe-attack)
**Triage SOC**

On colle des logs, l'outil sort les techniques **MITRE ATT&CK** détectées, les lignes qui les prouvent et les contre-mesures **D3FEND** à prioriser.

- 4 lectures du même incident : N1, N2, N3, responsable SOC
- Formats : syslog, auth.log, access.log, Sysmon, JSON (ECS), XML Windows
- Moteur **Sigma** : 6 règles maison + import SigmaHQ (1 439 règles sur 1 586 testées s'exécutent)

`JavaScript` · `MIT`

</td>
<td width="50%" valign="top">

### 🎯 [L'Orchestrateur](https://github.com/Mickaelb06/orchestrateur)
**Audit de sécurité automatisé**

À partir d'un domaine ou d'une IP, l'agent lance les outils de reconnaissance adaptés (nmap, DNS, en-têtes HTTP, SSL, CORS, e-mail security…) et génère un **rapport PDF**.

- Mapping **MITRE ATT&CK** de chaque constat
- Recommandations **ISO 27001, NIS 2, DORA**, référentiel NIST SP 800-53
- Modèle de langage exécuté en local : les données de l'audit restent privées

`Python`

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 🛡️ [FolderGuard](https://github.com/Mickaelb06/folderguard)
**Intégrité des fichiers et honeypot**

Deux petits outils de défense, construits pour comprendre la logique de détection d'un SOC.

- **`fim`** (Rust, en ligne de commande) : détecte les fichiers modifiés, ajoutés ou supprimés par rapport à une référence SHA-256
- **Honeypot SSH et telnet** : journalise les tentatives de connexion sans jamais ouvrir de terminal
- **Site web** : contrôle d'intégrité dans le navigateur (rien n'est envoyé) et tableau de bord du journal du honeypot

Mapping **MITRE ATT&CK** : T1565.001, T1070.004, T1554 (fim) · T1110, T1046, T1078 (honeypot)

`Rust` · `HTML/JS` · `MIT`

</td>
</tr>
</table>

---

## 🧭 Parcours

| | |
|---|---|
| **~7 ans** | Responsable informatique, des lycées Auguste Escoffier et Cadran Solaire ainsi que les Collèges Les Campelières et Frédéric Mistral (administration réseau) |
| **Aujourd'hui** | Auto-formation à l'analyse SOC (détection, MITRE ATT&CK, Sigma) et construction d'outils pour pratiquer |

## ⚙️ Comment je travaille

Je conçois, teste et relis mes outils moi-même, en développant avec un assistant IA comme copilote. Chaque ligne de code est relue et comprise avant d'être gardée, et les outils sont testés avant publication.

---

<div align="center">

### 📫 Me contacter

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mickael-0077B6?style=for-the-badge)](https://linkedin.com/in/mickaelbellaiche)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1220,100:0077b6&height=90&section=footer" alt="" />

</div>
