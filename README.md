
# Enterprise Cybersecurity Lab

## Présentation
Laboratoire personnel de cybersécurité reproduisant une infrastructure d'entreprise virtualisée sous VMware.

**Statut : En cours — 2026**

## Objectifs
- Construire un réseau d'entreprise isolé.
- Déployer Windows Server, Windows 11 et Linux.
- Configurer Active Directory et DNS.
- Réaliser des analyses de vulnérabilités avec Nessus.
- Étudier les journaux de sécurité et la détection d'incidents.

## Architecture prévue

| Machine | Rôle | Adresse IP |
|---|---|---|
| DC01 | Windows Server / AD DS / DNS | 192.168.10.10 |
| SRV01 | Ubuntu Server | 192.168.10.20 |
| WIN01 | Windows 11 | 192.168.10.30 |
| KALI01 | Kali Linux / outils de sécurité | 192.168.10.40 |

Réseau privé VMware : VMnet10 — 192.168.10.0/24.

## Avancement
- [x] Configuration du réseau VMnet10.
- [x] Connexion de DC01 au réseau privé.
- [ ] Déploiement Active Directory / DNS.
- [ ] Installation et configuration de Nessus.
- [ ] Analyse et remédiation des vulnérabilités.
- [ ] Collecte et analyse des logs de sécurité.

## Documentation
Les captures d'écran, procédures et résultats seront ajoutés progressivement.

## Cadre
Tests réalisés exclusivement dans un laboratoire isolé et autorisé.
  
