<div align="center">

  <h1>⚡ M3µD1 // Mehdi BEN MOULAY</h1>
  <p><strong>ADMINISTRATEUR SYSTÈMES & RÉSEAUX • AUTOMATISATION & CI/CD • CYBERSÉCURITÉ (SOC)</strong></p>

  <a href="https://m3hdi-sys.github.io/">
    <img src="https://img.shields.io/badge/🌐_PORTFOLIO_&_RAPPORTS-m3hdi--sys.github.io-38bdf8?style=for-the-badge&logoColor=white" alt="Portfolio" />
  </a>
  <a href="https://www.linkedin.com/in/mehdi-ben-moulay/">
    <img src="https://img.shields.io/badge/LINKEDIN-Mehdi_BEN_MOULAY-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:mbenmoulay04@gmail.com">
    <img src="https://img.shields.io/badge/EMAIL-mbenmoulay04@gmail.com-10b981?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>

</div>

<br>

<pre>
# /etc/sysadmin/mehdi-node.conf
Opérateur   : Mehdi BEN MOULAY (Alias : M3µD1)
Poste       : Administrateur Systèmes & Réseaux en Alternance @ Io.sys 2.21 (Paris)
Formation   : BTS SIO option SISR (2ème année @ Ingetis Paris)
Immersion   : Préparation Militaire Terre (PMT - 5 jours) @ 28e Régiment de Transmissions (Oct. 2026)
Spécialités : Virtualisation Proxmox LXC, Automatisation Python/Bash/n8n, GitLab CI/CD, Réseaux Cisco & SOC Wazuh
</pre>

---

### 🧱 Blocs Technologiques & Environnement Opérationnel

<div align="center">

**🖥️ SYSTÈMES, VIRTUALISATION & CONTENEURISATION**  
![Proxmox](https://img.shields.io/badge/Proxmox_VE-E57000?style=for-the-badge&logo=proxmox&logoColor=white)
![LXC](https://img.shields.io/badge/Conteneurs_LXC_(pct)-2496ED?style=for-the-badge&logo=linuxcontainers&logoColor=white)
![Linux Debian](https://img.shields.io/badge/Linux_Debian-A81D33?style=for-the-badge&logo=debian&logoColor=white)
![Systemd](https://img.shields.io/badge/Systemd_/_Journalctl-0F172A?style=for-the-badge&logo=linux&logoColor=FCC624)
![Windows Server](https://img.shields.io/badge/Windows_Server_/_11-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![VMware](https://img.shields.io/badge/VMware_/_Hyper--V-607078?style=for-the-badge&logo=vmware&logoColor=white)

**🌐 RÉSEAUX, ROUTAGE & HAUTE DISPONIBILITÉ**  
![Cisco](https://img.shields.io/badge/Cisco_(HSRP_/_VPN_IPsec_/_OSPF)-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![VLAN](https://img.shields.io/badge/TCP/IP_•_OSI_•_VLAN-1E293B?style=for-the-badge&logo=ubiquiti&logoColor=38BDF8)
![pfSense](https://img.shields.io/badge/pfSense_&_iptables-212121?style=for-the-badge&logo=pfsense&logoColor=white)
![SSH](https://img.shields.io/badge/SSH_&_Tunneling_TCP/UDP-0F172A?style=for-the-badge&logo=gnubash&logoColor=34D399)

**⚙️ AUTOMATISATION, CI/CD, SCRIPTS & CHATOPS**  
![Python](https://img.shields.io/badge/Python_(Asyncio_/_Regex_/_Discord.py)-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash_Scripting-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![GitLab CI/CD](https://img.shields.io/badge/GitLab_CI/CD_(Auto--Rollback)-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![n8n](https://img.shields.io/badge/n8n_(Workflows_&_IA_Appliquée)-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![Dev Web](https://img.shields.io/badge/JavaScript_/_PHP_/_SQL-334155?style=for-the-badge&logo=javascript&logoColor=F7DF1E)

**🛡️ SUPERVISION SOC, BLUE TEAM & INVESTIGATION**  
![Wazuh](https://img.shields.io/badge/Wazuh_SIEM_&_Sysmon-005571?style=for-the-badge&logo=elastic&logoColor=white)
![VirusTotal](https://img.shields.io/badge/VirusTotal_API-394EFF?style=for-the-badge&logo=virustotal&logoColor=white)
![MITRE](https://img.shields.io/badge/MITRE_ATT&CK_/_Blue_Team-1D4ED8?style=for-the-badge&logo=securityscorecard&logoColor=white)
![OSINT](https://img.shields.io/badge/OSINT_•_GeoINT_•_Forensic-111827?style=for-the-badge&logo=wireshark&logoColor=34D399)
![TryHackMe](https://img.shields.io/badge/TryHackMe-212C42?style=for-the-badge&logo=tryhackme&logoColor=C11111)

</div>

---

### 🏗️ Tableau d'Architecture de mes Projets Techniques

| Infrastructure / Projet | Réalisations Techniques | Technologies |
| :--- | :--- | :--- |
| **🐳 Homelab LXC Proxmox & Bot Discord (ChatOps)** | Déploiement de **5 conteneurs LXC isolés** (`pct`, IP statiques, démons `systemd`, tunneling TCP/UDP Playit). Développement d'un **Bot Discord Python** (`asyncio`, SSH par clés) pilotant les serveurs à distance : allumage via boutons, suivi des joueurs connectés (parsing `journalctl` par Regex), extinction auto sur inactivité et **backups/rollbacks toutes les 30 min** (`.tar.gz`). | `Proxmox VE` `LXC` `Python` `Bash` `Systemd` `SSH` |
| **🚀 Pipeline CI/CD & Mise en Production Auto** | Développement d'applications web et automatisation des déploiements sur **GitLab** : mises à jour automatiques en production, **système de rollback sur incident** et suivi centralisé des logs. | `GitLab CI/CD` `Docker` `Linux` `Python` `JS/SQL` |
| **🛡️ Déploiement Mini-SOC (Wazuh)** | Mise en place d'une infrastructure de détection et réponse aux incidents sur parc hybride (Windows/Linux) : règles XML sur-mesure (**MITRE ATT&CK / Atomic Red Team**), bannissement dynamique via `iptables` contre le brute-force, intégration **API VirusTotal** et alertes **Webhook Discord** en Python. | `Wazuh SIEM` `Sysmon` `VirusTotal API` `iptables` `Python` |
| **🌐 Réseau Cisco : HSRP & VPN Site-to-Site IPsec** | Mise en œuvre de la redondance réseau (**protocole HSRP** avec passerelle virtuelle et script Python de test de bascule Failover) et déploiement de **tunnels VPN Site-to-Site IPsec** / routage dynamique **OSPF** sur routeurs Cisco 1941. | `Cisco IOS` `HSRP` `VPN IPsec` `OSPF` |

---

### 🏆 Palmarès CTF, Forensics & Immersions Défense

<table>
  <tr>
    <td width="62%" valign="top">
      <ul>
        <li>🥇 <b>CTF Opération Culot (Bpifrance - BIG 2026)</b><br>
        • <code>8e / 21 équipes</code> en Finale Présentiel Hybride à l'Accor Arena<br>
        • <code>7e / 655 équipes</code> en mode Speed Runner<br>
        • <code>10e / 655 équipes</code> en ligne <i>(1900 pts • 7,41 % de fail • 0 hint)</i></li>
        <br>
        <li>🎯 <b>CTF Deep Threats (DGA & Campus OSINT | Sept. 2026)</b><br>
        • <code>184e / 487 équipes</code> <i>(626 pts — 22 challenges résolus sur l'investigation Marinatech Industries & Institut Lotus)</i></li>
        <br>
        <li>🔍 <b>Atelier Forensic (CyberSup Puteaux) & CTF GMP (2026)</b><br>
        • Investigation numérique (traçabilité, analyse d'en-têtes, extraction de métadonnées EXIF), GeoINT satellite et CTF du Gouvernement Militaire de Paris.</li>
      </ul>
    </td>
    <td width="38%" valign="top" align="center">
      <b>🎖️ OpenBadges Officiels & Attestations</b><br><br>
      <a href="https://badgify.eu/badge/55YMbzbd8hoQ3D2bdMBBtkv3DMTP4eqCUvWqe1oAAiYtViwIVhvDBUFianVkv25A">
        <img src="https://badgify.eu/uploads/badges/facfb4b8-248a-4a5a-b83f-8b0d5938ccb6.png" alt="Finisher" width="76" />
      </a>
      <a href="https://badgify.eu/badge/RV1vW7oFtl6JlJVa82bEqmQvf4jaPwuwu-Duh5YoH2J2aK8hMuJ-bNBqIh5VnmLJ">
        <img src="https://badgify.eu/uploads/badges/41202f39-7610-42cc-9b8c-d3c9a2293950.png" alt="Présentiel" width="76" />
      </a>
      <a href="https://badgify.eu/badge/RV1vW7oFtl6JlJVa82bEqmQvf4jaPwuwu-Duh5YoH2J2aK8hMuJ-bNBqIh5VnmLJ">
        <img src="https://badgify.eu/uploads/badges/4efbdc81-9d46-40c4-a91b-205cbf1029f9.png" alt="Participant" width="76" />
      </a>
      <br><br>
      <img src="https://img.shields.io/badge/28e_RT-Immersion_PMT_5_Jours_(Oct._2026)-10b981?style=flat-square" /><br>
      <img src="https://img.shields.io/badge/Les_Invalides-Journée_Immersion_Orion-38bdf8?style=flat-square" /><br>
      <img src="https://img.shields.io/badge/Cybermalveillance.gouv-Attestation_SensCyber-f59e0b?style=flat-square" />
    </td>
  </tr>
</table>
