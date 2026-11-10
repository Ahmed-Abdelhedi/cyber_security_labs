# Sécurité des systèmes Linux

Les exercices SELinux et SSH abordent directement les contrôles de sécurité. La gestion des utilisateurs, des processus, des services et du stockage complète les bases d'administration nécessaires pour comprendre et maintenir un système Linux.

**Outils et notions :** Linux, SELinux, OpenSSH, systemd, LVM.

## Contrôle d'accès avec SELinux

| Rapport | Contenu |
| --- | --- |
| [Modes de fonctionnement de SELinux](selinux/selinux-operating-modes.pdf) | Observation et changement des modes Enforcing et Permissive. |
| [Contextes de fichiers SELinux](selinux/selinux-file-contexts.pdf) | Étiquetage et accès à une racine web personnalisée. |
| [Booléens de politique SELinux](selinux/selinux-policy-booleans.pdf) | Ajustement des autorisations liées à un service Apache. |
| [Diagnostic des refus SELinux](selinux/selinux-troubleshooting.pdf) | Analyse des journaux et résolution de problèmes d'accès. |
| [Administration de la sécurité avec SELinux](selinux/selinux-security-management.pdf) | Mise en pratique des contextes et de l'analyse des alertes. |

## Administration distante avec SSH

| Rapport | Contenu |
| --- | --- |
| [Gestion des clés d'hôte SSH](ssh/ssh-host-key-management.pdf) | Identification des serveurs et gestion des clés connues. |
| [Authentification SSH par clé](ssh/ssh-key-based-authentication.pdf) | Configuration de l'accès distant avec une paire de clés. |
| [Configuration et sécurisation de SSH](ssh/ssh-configuration-and-hardening.pdf) | Mise en pratique de la configuration du service SSH. |

## Utilisateurs et groupes

| Rapport | Contenu |
| --- | --- |
| [Utilisateurs et groupes locaux Linux](identity-and-access/linux-local-users-and-groups.pdf) | Administration des comptes et des appartenances aux groupes. |

## Processus et services

| Rapport | Contenu |
| --- | --- |
| [Contrôle des tâches Linux](processes-and-services/linux-job-control.pdf) | Gestion des tâches en avant-plan et en arrière-plan. |
| [Signaux et processus Linux](processes-and-services/linux-process-signals.pdf) | Envoi de signaux pour contrôler l'exécution des processus. |
| [Surveillance de l'activité des processus](processes-and-services/linux-process-activity-monitoring.pdf) | Observation des processus et de leur activité. |
| [Surveillance et gestion des processus](processes-and-services/linux-process-monitoring-and-management.pdf) | Travail de synthèse sur l'administration des processus Linux. |
| [Identification des processus au démarrage](processes-and-services/linux-startup-processes.pdf) | Repérage des processus et services lancés automatiquement. |
| [Gestion des services système](processes-and-services/linux-system-service-management.pdf) | Contrôle des services avec systemd. |
| [Services et démons Linux](processes-and-services/linux-services-and-daemons.pdf) | Mise en pratique de l'administration des services. |

## Stockage et fichiers

| Rapport | Contenu |
| --- | --- |
| [Gestion des fichiers en ligne de commande](storage-and-files/linux-command-line-file-management.pdf) | Manipulation de fichiers et navigation dans le système de fichiers. |
| [Création de volumes logiques LVM](storage-and-files/lvm-logical-volume-creation.pdf) | Partitions, volumes physiques, groupes et volumes logiques. |
| [Extension d'un volume logique LVM](storage-and-files/lvm-logical-volume-extension.pdf) | Ajout de capacité et agrandissement d'un volume. |
| [Gestion du stockage avec LVM](storage-and-files/lvm-storage-management.pdf) | Mise en pratique de l'administration du stockage logique. |

## Illustration complémentaire

[Exemple de session distante SSH](ssh/assets/ssh-remote-session.jpg) : capture de connexion à un serveur de laboratoire.

[Retour au catalogue principal](../README.md)
