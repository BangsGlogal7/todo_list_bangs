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

# les données que notre application va manipuler V1

# les Objets metiers:
Todo App

│

├── User

├── Project

├── Task

└── Attachment

# Objet 1 : User
User

id

name

email

createdAt

# Objet 2 : Project
Project

id

name

color

icon

description

createdAt

updatedAt

# Objet 3 : Task
Task

id

title

description

status

priority

dueDate

estimatedTime

reminder

projectId

attachments

createdAt

updatedAt

# Objet 4 : Attachment(piece joinde)
Attachment

id

fileName

fileType

fileSize

url

createdAt

# Les relations

Maintenant dessinons les relations.
User

│

├───────────┐

│           │

▼           ▼

Project     Project

│

├──────────────┐

│              │

▼              ▼

Task          Task

│

├──────┐

│      │

▼      ▼

Attachment

# Notre cahier des charges V1
Statuts
✅ To Do
✅ In Progress
✅ Done
Priorités
✅ Low
✅ Medium
✅ High
Champs d'une tâche
✅ id
✅ title
✅ description (facultatif)
✅ status
✅ priority
✅ dueDate (facultatif)
✅ reminder (facultatif)
✅ estimatedTime (facultatif)
✅ attachments (prévu, avec une implémentation simple en V1)
✅ projectId
✅ createdAt
✅ updatedAt
Fonctionnalités V1
✅ Ajouter une tâche
✅ Modifier une tâche
✅ Supprimer une tâche
✅ Rechercher une tâche
✅ Filtrer les tâches
✅ Sauvegarder avec LocalStorage
✅ Interface responsive (desktop et mobile)