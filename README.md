# To-Do List Manager 📝

Une application web de gestion de tâches développée avec Ruby dans le cadre de la formation Le Wagon. Cette application permet de créer, organiser et suivre vos tâches quotidiennes de manière simple et efficace.

## 📋 Table des matières
1. [Présentation du projet](#présentation-du-projet)
2. [Fonctionnalités](#fonctionnalités)
3. [Technologies utilisées](#technologies-utilisées)
4. [Installation](#installation)
5. [Structure du projet](#structure-du-projet)
6. [Apprentissages](#apprentissages)
7. [License](#license)

## 🎯 Présentation du projet

Ce projet a été réalisé dans le cadre de la formation de développement web du Wagon. L'objectif était de créer une application web de gestion de tâches permettant aux utilisateurs de gérer efficacement leurs to-do lists quotidiennes, en découvrant le framework Rails.

## ✨ Fonctionnalités

- Création de tâches avec titre et description
- Marquage des tâches comme terminées
- Interface utilisateur intuitive et responsive

## 🛠 Technologies utilisées

- Ruby v3.1.2
- Ruby on Rails v7.0.4
- SQLlite
- HTML5
- CSS3 / SCSS
- JavaScript
- Bootstrap
- Git/GitHub

## ⚙️ Installation

```bash
# Cloner le repository
git clone https://github.com/ClarisseKessab/rails-task-manager.git

# Accéder au dossier
cd rails-task-manager

# Installer les dépendances
bundle install

# Créer la base de données
rails db:create

# Effectuer les migrations
rails db:migrate

# Lancer le serveur
rails server
```

L'application sera accessible à l'adresse `http://localhost:3000`

## 📁 Structure du projet

```
todo-list-wagon/
├── app/
│   ├── controllers/
│   ├── models/
│   ├── views/
│   └── assets/
├── config/
├── db/
├── Gemfile
└── README.md
```

## 📚 Apprentissages

Ce projet m'a permis de mettre en pratique :
- La création d'une application Ruby on Rails complète
- La gestion d'une base de données avec SQL Lite
- L'implémentation d'un CRUD (Create, Read, Update, Delete)
- L'utilisation de Bootstrap pour un design responsive
- Le travail avec Git pour la gestion de versions

## 📝 License

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.

---
Développé avec ❤️ pendant la formation Le Wagon
