# Projet Ansible - Hardening & Automation CI/CD

Ce projet automatise la sécurisation d'un serveur Linux et valide la conformité du code via un pipeline GitHub Actions.

## Structure du dépôt
- `.github/workflows/ansible-ci.yml` : Workflow d'intégration continue (ansible-lint).
- `inventory/web/hosts.ini` : Fichier d'inventaire ciblant l'environnement Vagrant.
- `hardening_system.yml` : Playbook de sécurisation système (SSH, /etc/shadow).

## Préréquis
- Ansible 2.10+
- Ansible-Lint
- Vagrant & VirtualBox

## Utilisation

1. **Vérifier la connectivité des hôtes :**
