# Sécurité réseau

Les rapports couvrent la configuration de pare-feu, l'exposition contrôlée de services et la protection des communications. Les analyses Wireshark permettent d'observer les protocoles et de comparer les échanges Telnet et SSH.

**Outils et notions :** Huawei USG6510E, IPsec, SSL VPN, Wireshark.

## Pare-feu et NAT

| Rapport | Contenu |
| --- | --- |
| [Pare-feu NGFW : filtrage et inspection TLS](firewalls/ngfw-traffic-filtering-and-tls-inspection.pdf) | Zones de sécurité, filtrage applicatif et inspection du trafic. |
| [Source NAT et publication d'un serveur en DMZ](firewalls/firewall-source-nat-and-dmz-server-publishing.pdf) | Traduction d'adresses, NAT Server et observation du trafic FTP. |

## Réseaux privés virtuels

| Rapport | Contenu |
| --- | --- |
| [VPN IPsec de site à site](vpn/ipsec-site-to-site-vpn.pdf) | Passerelles Huawei, IKE et associations de sécurité. |
| [Accès distant par VPN SSL](vpn/ssl-vpn-remote-access.pdf) | SecoClient, authentification et accès à l'intranet par tunnel TLS. |

## Analyse de trafic

| Rapport | Contenu |
| --- | --- |
| [Capture et analyse de paquets avec Wireshark](traffic-analysis/wireshark-packet-capture-and-analysis.pdf) | Observation des adresses, des trames et des échanges ICMP. |
| [Comparer Telnet et SSH dans Wireshark](traffic-analysis/wireshark-telnet-vs-ssh.pdf) | Visibilité des données en clair et protection des échanges par SSH. |

[Retour au catalogue principal](../README.md)
