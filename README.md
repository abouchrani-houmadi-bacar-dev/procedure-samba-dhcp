# Procédure d'installation Samba & DHCP
## IUT de Saint-Pierre, La Réunion | SAÉ 2.04 | Juin 2026

## Contexte
Mise en place d'un environnement réseau centralisé avec partage de fichiers
et attribution automatique d'adresses IP pour un établissement scolaire.

## Ce que contient ce dépôt
- `procedure_samba_dhcp.pdf` — Procédure complète d'installation et vérification

## Ce qui a été mis en place
- Serveur DHCP (plage 192.168.1.100-200)
- Partages de fichiers Samba (étudiants, directeur, espace commun)
- Quotas disque (2 Mo/étudiant, 5 Mo/directeur)
- Gestion des utilisateurs et groupes Linux

## Outils utilisés
- Debian Linux
- isc-dhcp-server
- Samba / SMB

## Auteurs
BOUCHRANI Ambdouroihamane · DILMAHAMOD Réhaan · 
GALANT Adame · SAUTRON-CICIA Markus
