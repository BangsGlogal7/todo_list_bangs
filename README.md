# todo_list_bangs
Projet : Todo List Professionnelle (JavaScript) Technologies  Pendant tout ce projet, nous utiliserons uniquement :  HTML5 CSS3 JavaScript (ES6+) LocalStorage

# Fonctionnalités :
Dashboard
Sidebar
Recherche
Ajouter une tâche
Modifier une tâche
Supprimer une tâche
Filtrer
Trier
Catégories
Statut
Date limite
Responsive Desktop

# Fonctionnalités :

Responsive
Menu mobile
Ajout rapide
Formulaire optimisé

# Architecture du projet

todo-app-js/
│
├── README.md
├── package.json
├── .gitignore
│
├── src/
│   │
│   ├── index.html
│   │
│   ├── assets/
│   │   ├── images/
│   │   ├── icons/
│   │   └── fonts/
│   │
│   ├── css/
│   │   ├── base/
│   │   │   ├── reset.css
│   │   │   ├── variables.css
│   │   │   └── typography.css
│   │   │
│   │   ├── layout/
│   │   │   ├── sidebar.css
│   │   │   ├── header.css
│   │   │   ├── grid.css
│   │   │   └── responsive.css
│   │   │
│   │   ├── components/
│   │   │   ├── button.css
│   │   │   ├── card.css
│   │   │   ├── modal.css
│   │   │   ├── form.css
│   │   │   ├── badge.css
│   │   │   └── task.css
│   │   │
│   │   └── style.css
│   │
│   └── js/
│       │
│       ├── app.js
│       ├── main.js
│       │
│       ├── models/
│       │   ├── Task.js
│       │   └── Project.js
│       │
│       ├── services/
│       │   ├── taskService.js
│       │   ├── storageService.js
│       │   └── searchService.js
│       │
│       ├── ui/
│       │   ├── sidebar.js
│       │   ├── header.js
│       │   ├── modal.js
│       │   ├── taskList.js
│       │   └── dashboard.js
│       │
│       ├── utils/
│       │   ├── constants.js
│       │   ├── helpers.js
│       │   ├── validators.js
│       │   └── date.js
│       │
│       └── data/
│           └── demoData.js

