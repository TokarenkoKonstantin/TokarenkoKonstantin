<div align="center">

[🇬🇧 English](https://github.com/TokarenkoKonstantin/TokarenkoKonstantin/blob/main/README.md) &nbsp;|&nbsp; 🇷🇺 Русский

# Константин Токаренко

### DevOps-инженер

*Строю production-инфраструктуру с нуля — Kubernetes · CI/CD · IaC · Мониторинг*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-konstantin--tokarenko-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/konstantin-tokarenko)
[![Telegram](https://img.shields.io/badge/Telegram-@KonstantinTokar-2CA5E0?style=flat&logo=telegram&logoColor=white)](https://t.me/KonstantinTokar)
[![Email](https://img.shields.io/badge/Email-consttokarenko%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:consttokarenko@gmail.com)
![Open to Work](https://img.shields.io/badge/Открыт%20к%20работе-brightgreen?style=flat)

</div>

---

## 🚀 Ключевые проекты

### ☸️ [cloud-shop](https://github.com/TokarenkoKonstantin/cloud-shop) — Kubernetes на железе, с нуля

> Production-кластер K8s, собранный **руками через kubeadm** на 5 VM — глубоко, без магии.

- ☸️ **Кластер** — 5 VM (kubeadm): 1 master + 4 worker, **Calico** CNI, **MetalLB** LoadBalancer
- 🔄 **GitOps CI/CD** — GitHub Actions → GHCR → **ArgoCD** автосинк → кластер
- 🗄️ **PostgreSQL HA** — CloudNativePG: 1 primary + 2 реплики, автобэкапы в MinIO
- 📊 **Мониторинг** — Prometheus + Grafana, Node Exporter, свои дашборды
- 🏗️ **IaC** — Terraform + Ansible (полная автоматизация кластера)
- 🛡️ **Безопасность и HA** — Trivy CVE-сканирование, HPA (3→10), PDB, Ingress-NGINX

### ☁️ [cloud-shop-aws](https://github.com/TokarenkoKonstantin/cloud-shop-aws) — Та же идея, облачно на AWS

> Та же e-commerce платформа, переархитектурированная на **managed-сервисы AWS** через Terraform.

- ☁️ **EKS** кластер + managed node groups, **IRSA** (IAM на уровне подов)
- 🗄️ **RDS** PostgreSQL · **ECR** реестры · **VPC** (public/private подсети, NAT)
- 🏗️ **Terraform** модули + remote state (S3 + блокировка через DynamoDB)
- 🔄 **GitOps** на ArgoCD, пайплайн GitHub Actions

> **Вместе они показывают широту** — Kubernetes на железе руками **и** облачная managed-инфраструктура: одно приложение, два реальных подхода.

---

## 🛠 Стек

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![ArgoCD](https://img.shields.io/badge/ArgoCD-EF7B4D?style=flat&logo=argo&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI-FC6D26?style=flat&logo=gitlab&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat&logo=ansible&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat&logo=nginx&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat&logo=helm&logoColor=white)

---

## 📊 Активность на GitHub

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=TokarenkoKonstantin&show_icons=true&theme=dark&hide_border=true&include_all_commits=true&count_private=true" alt="GitHub Stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=TokarenkoKonstantin&layout=compact&theme=dark&hide_border=true&langs_count=8" alt="Top Languages" />
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=TokarenkoKonstantin&theme=dark&hide_border=true&date_format=j%20M%5B%20Y%5D" alt="GitHub Streak" />
</div>

---

## 📬 Контакты

| | |
|---|---|
| 💼 LinkedIn | [konstantin-tokarenko](https://linkedin.com/in/konstantin-tokarenko) |
| 💬 Telegram | [@KonstantinTokar](https://t.me/KonstantinTokar) |
| 📧 Email | consttokarenko@gmail.com |
| 📍 Локация | Россия · Открыт к удалёнке (EU) |
