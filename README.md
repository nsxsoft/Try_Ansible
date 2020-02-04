# Try_Ansible
## Projet : NginxPhp
Déploiement d'un serveur web sous Nginx et php-fpm.

### Environnement utilisé
- Vagrant 2.2.7
- Ansible 2.9.4
- VirtualBox 6.0

### Personnalisation du déploiement
La personnalisation de la configuration s'opère au niveau du fichier **vars/main.yml**.
L'hôte virtuel et la version de PHP sont indiqués dans ce fichier.

La configuration de l'hôte virtuel est généré à partir du fichier **templates/example.local.j2**.

Les fichiers web déployés se situent sous **files/html/**.
Par défaut, une page web simple et une page php sont déployés.

La configuration du serveur web se situe sous **files/nginx/**.
