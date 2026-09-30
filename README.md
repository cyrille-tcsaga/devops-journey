# DevOps Journey

Ce projet est un journal de bord de mon apprentissage du DevOps. Il est organisé en phases, chacune correspondant à un ensemble de compétences à acquérir. Chaque phase contient des objectifs spécifiques et des ressources pour les atteindre.

## Objectifs

* Obtenir la certifications AWS Solutions Architect Associate
* Maitriser CI/CD avec Github Actions
* Maitriser Docker et Kubernetes
* Deployer des applications sur le cloud AWS

## Auto évaluation (Octobre 2026)

* Linux: 3/5
* Réseau: 2/5
* Docker: 3/5
* CI/CD: 2/5
* Git: 4/5
* Bash: 1/5
* Kubernetes: 2/5

## Plan des phases

01. **Phase 1: Demarrage**  
    - [*] Auto-évaluation des compétences
    - [*] Installer Ubuntu 26.04 LTS sur mon PC
    - [*] Créer le depot GitHub pour le projet
    - [*] Créer un compte AWS et configurer le MFA
    - [*] Configurer AWS Budgets avec une alerte de 5$

02. **Phase 2: Linux et terminal**  
    - [ ] Système de fichiers et navigation (ls, cd, find, arborescence FHS)
    - [ ] Permissions : chmod, chown, utilisateurs, groupes, sudo
    - [ ] Gestion des paquets avec apt
    - [ ] Bases de Vim (ou Nano) pour éditer sur un serveur
    - [ ] Processus : ps, top, htop, kill, signaux
    - [ ] Services avec systemd et logs avec journalctl
    - [ ] Performance : free, df, du, vmstat, iostat
    - [ ] Tâches planifiées avec cron
    - [ ] Manipulation de texte : grep, sed, awk, cut, sort, uniq
    - [ ] Pipes et redirections
    - [ ] Outils réseau : ping, curl, dig, ss, traceroute
    - [ ] SSH : clés, fichier config, désactiver la connexion root

03. **Phase 3: Réseau et protocoles**  
    - [ ] Modele OSI et modèle TCP/IP
    - [ ] Adresses IP, sous-réseaux et notation CIDR
    - [ ] Ports, TCP contre UDP, NAT
    - [ ] DNS : fonctionnement et enregistrements A, CNAME, MX, TXT
    - [ ] HTTP et HTTPS : méthodes, codes, en-têtes
    - [ ] SSL/TLS et certificats
    - [ ] SSH, FTP et SFTP
    - [ ] Email : SMTP, IMAP, POP3S, SPF, DKIM, DMARC

04. **Phase 4: Bash et Git avancé**
    - [ ] Variables, conditions, boucles, fonctions
    - [ ] Arguments, codes de retour, set -euo pipefail
    - [ ] Vérifier tes scripts avec ShellCheck
    - [ ] Branches, merge, rebase, résolution de conflits
    - [ ] Stratégies : GitFlow et trunk-based
    - [ ] Tags, hooks, GitHub et GitLab

05. **Phase 5: Python pour l'automatisation**  
    - [ ] Syntaxe, variables, types, conversion de types
    - [ ] Conditions, boucles, fonctions
    - [ ] Listes, tuples, sets, dictionnaires, compréhensions de listes
    - [ ] Exceptions
    - [ ] Modules, pip, venv, uv et pyproject.toml
    - [ ] Fichiers, JSON, YAML, variables d'environnement
    - [ ] Appels HTTP avec requests, arguments avec argparse
    - [ ] Expressions régulières et context managers
    - [ ] Classes : les bases seulement
    - [ ] Tests avec pytest, formatage avec ruff
    - [ ] Construire le livrable

06. **Phase 6: Serveurs web**  
    - [ ] Nginx : server blocks et reverse proxy vers Spring Boot
    - [ ] HTTPS avec Let's Encrypt (Certbot)
    - [ ] Caddy en comparaison
    - [ ] Load balancer avec Nginx upstream
    - [ ] Cache côté serveur, forward proxy contre reverse proxy
    - [ ] Pare-feu : ufw et bases d'iptables, fail2ban

07. **Phase 7: Conteneurs Docker**  
    - [ ] Images, conteneurs, couches, Dockerfile
    - [ ] Volumes et réseaux Docker
    - [ ] Builds multi-étapes et réduction de la taille des images
    - [ ] Docker Compose, variables d'environnement, healthchecks
    - [ ] Registres : Docker Hub et GitHub Container Registry
    - [ ] Sécurité : utilisateur non root, scan avec Trivy
    - [ ] LXC : comprendre la différence avec Docker

08. **Phase 8: Intégration et déploiement continus**  
    - [ ] Concepts CI/CD
    - [ ] GitHub Actions : workflows, jobs, secrets, cache, matrices
    - [ ] GitLab CI en comparaison, Jenkins en notions
    - [ ] Gestion d'artefacts (notion de Nexus)
    - [ ] Stratégies de déploiement : rolling, blue green, canary

09. **Phase 9: AWS et certification Solutions Architect**
    - [ ] IAM : utilisateurs, rôles, politiques, MFA
    - [ ] AWS CLI, régions et zones de disponibilité
    - [ ] VPC : sous-réseaux publics et privés, tables de routage
    - [ ] Internet Gateway, NAT Gateway, Security Groups, NACL
    - [ ] EC2, EBS, AMI
    - [ ] Auto Scaling et Load Balancers (ALB, NLB)
    - [ ] S3 : classes de stockage, versioning, cycle de vie, politiques
    - [ ] CloudFront et Route 53
    - [ ] RDS et Aurora
    - [ ] DynamoDB et ElastiCache
    - [ ] Lambda, API Gateway, SQS, SNS, EventBridge
    - [ ] ECS et Fargate
    - [ ] Piloter AWS en Python avec boto3
    - [ ] CloudWatch, CloudTrail, KMS, Secrets Manager
    - [ ] Well-Architected Framework et cloud design patterns
    - [ ] Examens blancs : viser 80% minimum
    - [ ] Lister tes points faibles
    - [ ] Révision ciblée des points faibles
    - [ ] Nouveaux examens blancs
    - [ ] Passer l'examen AWS SAA-C03

10. **Phase 10: Infrastructure as Code**  
    - [ ] Terraform : providers, ressources, variables, outputs, state
    - [ ] Terraform : modules, state distant sur S3 avec verrou, workspaces
    - [ ] CloudFormation, CDK et Pulumi : savoir les situer
    - [ ] Ansible : inventaire, playbooks, rôles, idempotence
    - [ ] Construire le livrable

11. **Phase 11: Kubernetes et GitOps**  
    - [ ] Architecture, pods, deployments, services, namespaces (avec kind ou minikube)
    - [ ] ConfigMaps, Secrets, volumes
    - [ ] Ingress et probes
    - [ ] Helm
    - [ ] Ressources, limites et autoscaling (HPA)
    - [ ] EKS provisionné avec Terraform
    - [ ] ECS contre EKS : quand choisir lequel
    - [ ] GitOps avec ArgoCD

12. **Phase 12: Observabilité, monitoring et secrets**  
    - [ ] Prometheus et Grafana, règles d'alerte
    - [ ] Zabbix : notion
    - [ ] Logs avec Loki (ou Elastic Stack)
    - [ ] Traces avec OpenTelemetry et Jaeger
    - [ ] Vault, Sealed Secrets, SOPS
    - [ ] AWS Secrets Manager en pratique

13. **Phase 13: Projet final et portfolio**  
    - [ ] AutoKool prêt pour la production : IaC, CI/CD, Kubernetes, monitoring, sauvegardes
    - [ ] Analyse et optimisation des coûts AWS
    - [ ] Schéma d'architecture et documentation complète
    - [ ] Article ou vidéo sur le projet
    - [ ] Mise à jour du CV et du profil LinkedIn

## Ressources

    - [Linux Journey](https://linuxjourney.com/)
    - [The Linux Command Line](https://linuxcommand.org/tlcl.php)
    - [Docker Documentation](https://docs.docker.com/)
    - [Kubernetes Documentation](https://kubernetes.io/docs/home/)
    - [AWS Documentation](https://docs.aws.amazon.com/)
    - [Terraform Documentation](https://developer.hashicorp.com/terraform/docs)
    - [Ansible Documentation](https://docs.ansible.com/)
    - [GitHub Actions Documentation](https://docs.github.com/en/actions)
    - [GitLab CI Documentation](https://docs.gitlab.com/ee/ci/)
    - [Jenkins Documentation](https://www.jenkins.io/doc/)
    - [Prometheus Documentation](https://prometheus.io/docs/introduction/overview/)
    - [Grafana Documentation](https://grafana.com/docs/)
    - [Zabbix Documentation](https://www.zabbix.com/documentation/current/manual)
    - [Loki Documentation](https://grafana.com/docs/loki/latest/)
    - [OpenTelemetry Documentation](https://opentelemetry.io/docs/)
    - [Vault Documentation](https://www.vaultproject.io/docs)
    - [Sealed Secrets Documentation](https://github.com/bitnami-labs/sealed-secrets)
    - [SOPS Documentation](https://github.com/mozilla/sops)

## Contribuer

> Vous pouvez cloner le dépôt dans votre propre compte GitHub et commencer à travailler sur votre propre dépôt. Ne soumettez pas de pull requests sur ce dépôt. Merci pour votre compréhension.

## Licence

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
