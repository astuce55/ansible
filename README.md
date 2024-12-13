# Installation de Docker avec Ansible

Ce projet utilise un playbook Ansible pour installer et configurer Docker sur une machine Ubuntu. Le playbook est conçu pour être exécuté depuis une machine hôte afin de déployer Docker sur une machine distante (ma VM dans VirtualBox).

---

## 📋 Prérequis

1. **Machine hôte** :
   - Ansible installé.
   - Accès SSH configuré pour la machine distante (connexion par clé SSH recommandée).

2. **Machine distante (VM Ubuntu)** :
   - Ubuntu 20.04 ou version ultérieure.
   - Service SSH actif et accessible.

3. **Réseau** :
   - La machine hôte doit pouvoir communiquer avec la machine distante via SSH.
   - (Optionnel) Configuration réseau dans VirtualBox (mode NAT ou Réseau bridgé).

---

