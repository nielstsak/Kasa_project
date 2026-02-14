Projet Kasa

Bienvenue sur le projet Kasa, une application web dynamique permettant aux utilisateurs de consulter, rechercher et explorer des propriétés à louer. Le projet est structuré autour d'une architecture React pour le frontend, avec un backend en Node.js, et peut être lancé via Docker ou localement en utilisant npm.

🚀 Technologies utilisées

Frontend : React, React Router DOM, CSS Modules

Backend : Node.js

Outils de développement : Docker, npm, Vite, Testing Library

📁 Structure du projet

my-react-app
├── src
│   ├── assets
│   ├── components
│   ├── data
│   ├── layouts
│   ├── pages
│   ├── router
│   └── tests
├── index.html
├── vite.config.js
├── package.json
└── README.md

🛠️ Installation locale

1. Clonez le dépôt

git clone https://github.com/nielstsak/Kasa_project.git
cd my-react-app

2. Installez les dépendances

npm install

3. Lancez le Backend

Dans un terminal séparé, démarrez votre backend :

npm start

Le backend démarre sur le port 8080 par défaut.

4. Lancez le Frontend

Dans un autre terminal, lancez le frontend en mode développement :

npm run dev

Votre application sera accessible à l'adresse :

http://localhost:5173

🐳 Lancer avec Docker

Si vous préférez utiliser Docker, suivez ces étapes :

1. Créez une image Docker

docker build -t kasa-app .

2. Lancez le conteneur Docker

docker run -d -p 8080:8080 -p 5173:5173 kasa-app

Votre application Dockerisée est accessible via :

Frontend : http://localhost:5173
Backend  : http://localhost:8080

🧪 Tests unitaires

Pour exécuter les tests unitaires et vérifier le bon fonctionnement des composants React, utilisez :

npm test

Ces tests utilisent Testing Library.

📖 Fonctionnalités principales

Consultation de propriétés détaillées avec images et équipements

Recherche et filtrage intuitifs

Navigation dynamique et responsive

Gestion des erreurs avec une page personnalisée

🎯 Bonnes pratiques utilisées

Responsive Design pour assurer une compatibilité optimale sur mobile, tablette et desktop

CSS Modules pour isoler efficacement les styles CSS

React Router DOM pour une gestion fluide et efficace de la navigation côté client

Gestion des états internes grâce aux Hooks React (useState, useEffect, etc.)

Docker pour garantir une facilité de déploiement et une cohérence des environnements

📝 Auteur


 Tsakiris Niels   
