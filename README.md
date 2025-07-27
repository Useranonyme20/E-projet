# E-projet

# 📂 Projet : Application de gestion de projets – DGTCP

Une application web pour gérer les projets au sein d’une administration publique, avec un système de validation hiérarchique (agent → chef de service → directeur), conçue dans le cadre de ma licence professionnelle à l’ESCAE-Bénin.

---

## 🚀 Fonctionnalités principales

- Création et suivi de projets
- Système de validation par niveau hiérarchique
- Historique des actions et des statuts
- Authentification par rôle (agent, chef de service, directeur)
- Notifications de validation / modification
- Gestion des documents joints
- Prise en compte des congés dans le workflow

---

## 🛠️ Technologies utilisées

- **Framework** : Laravel 12  
- **Langages** : PHP, HTML, CSS, JavaScript  
- **Base de données** : MySQL  
- **Outils** : Git, VS Code

---

## 📦 Installation locale

```bash
git clone https://github.com/samia-projets/gestion-projets-dgtcp.git
cd gestion-projets-dgtcp
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
