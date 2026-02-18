# VPN WireGuard Lab 🌐🔐

Dans ce projet, je mets en place un VPN sécurisé avec WireGuard dans un environnement virtuel.

## Objectif

Comprendre le fonctionnement d’un VPN et sécuriser la communication entre deux machines.

## Architecture

- 1 serveur WireGuard (Ubuntu)
- 1 client
- Communication chiffrée via UDP

## Environnement

- Machines virtuelles (VirtualBox)
- Ubuntu Server
- Réseau interne isolé

---

## 1. Installation de WireGuard

```bash
sudo apt update
sudo apt install wireguard
