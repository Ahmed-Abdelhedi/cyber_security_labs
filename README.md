# Cybersecurity Labs

**Ahmed Abdelhedi** — Portfolio de travaux pratiques et d'analyses en cybersécurité.

Ce dépôt rassemble 44 rapports PDF classés par domaine de compétence : protection des réseaux, détection d'intrusions, sécurité Linux, cryptographie, évaluation de la sécurité, automatisation et gouvernance. Chaque domaine dispose d'un catalogue avec des liens directs vers ses rapports.

Les livrables comprennent des comptes rendus avec captures d'écran et des analyses documentaires. Les catalogues décrivent le sujet de chaque rapport et les outils étudiés.

## Catalogue

| Domaine | Sujets couverts | Rapports |
| --- | --- | ---: |
| [Sécurité réseau](network-security/README.md) | Filtrage réseau, traduction d'adresses, tunnels VPN et analyse de trafic. | 6 |
| [Détection et supervision de sécurité](detection-and-monitoring/README.md) | Détection et prévention d'intrusions, observation des postes et analyse d'alertes. | 4 |
| [Sécurité des systèmes Linux](system-security/README.md) | Contrôles d'accès, administration SSH, processus, services et stockage Linux. | 20 |
| [Cryptographie et intégrité des données](cryptography/README.md) | Hachage, vérification d'intégrité et chiffrement de données. | 2 |
| [Évaluation de la sécurité](security-assessment/README.md) | Reconnaissance réseau et étude des injections SQL en laboratoire. | 2 |
| [Automatisation de l'administration](security-automation/README.md) | Installation d'Ansible, inventaires, configuration et exécution de playbooks. | 6 |
| [Gouvernance, risque et conformité](governance-risk-and-compliance/README.md) | Gouvernance de la cybersécurité, cadre tunisien et preuves électroniques. | 4 |

## Organisation

```text
network-security/                  Pare-feu, VPN et analyse de trafic
detection-and-monitoring/           IDS, IPS et observables des postes
system-security/                   SELinux, SSH et administration Linux
cryptography/                      Hachage, intégrité et chiffrement
security-assessment/               Reconnaissance et injections SQL
security-automation/               Administration automatisée avec Ansible
governance-risk-and-compliance/     Gouvernance et cadre juridique
```

Les exercices d'administration Linux et Ansible apportent les bases opérationnelles utiles aux travaux de sécurité. Les catalogues précisent le contenu de chaque rapport.

## Repères de lecture

- **Protection des infrastructures :** [pare-feu et VPN](network-security/README.md), puis [SELinux et SSH](system-security/README.md).
- **Observation et détection :** [analyse de trafic](network-security/README.md#analyse-de-trafic), puis [Suricata, Snort et osquery](detection-and-monitoring/README.md).
- **Évaluation et protection des données :** [Nmap et injections SQL](security-assessment/README.md), puis [hachage et chiffrement](cryptography/README.md).
- **Administration et gouvernance :** [Ansible](security-automation/README.md) et [analyses de gouvernance et du cadre juridique](governance-risk-and-compliance/README.md).

## Conventions

- Dossiers organisés par domaine de cybersécurité et sous-thème.
- Noms descriptifs en anglais, en minuscules, sans espaces ni accents, avec des tirets (`kebab-case`).
- Rapports au format PDF et documentation de navigation au format Markdown.
- Auteurs, coauteurs et références conservés dans les documents.

## Contexte des travaux

Les scénarios techniques décrivent des environnements de laboratoire ; certaines étapes illustrent volontairement des configurations non sécurisées. Les analyses réglementaires reflètent le contexte de rédaction indiqué dans leurs sources.

Les outils étudiés comprennent notamment Huawei USG6510E, Wireshark, Suricata, Snort, osquery, SELinux, OpenSSH, Nmap, MySQL et Ansible.
