# Billed — Plateforme de Gestion de Notes de Frais
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=for-the-badge&logo=jest&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)

**Billed** est une application SaaS interne destinée aux ressources humaines, permettant aux employés de soumettre leurs notes de frais et aux administrateurs de les valider. Ce projet se concentre sur le **débogage** et les **tests unitaires et d'intégration** pour garantir la fiabilité d'une plateforme critique.

---

## 📌 Présentation du Projet
L'objectif de ce projet était de reprendre une application existante présentant des bugs et une couverture de tests insuffisante. En tant que développeur, ma mission consistait à :
- Identifier et corriger des bugs fonctionnels (logique de tri, formulaires, etc.).
- Implémenter des tests unitaires et d'intégration avec **Jest**.
- Augmenter la couverture de tests pour les composants clés du frontend.
- Rédaction d'un plan de test pour assurer la non-régression.

---

## 🎯 Objectifs techniques
- **Débogage Avancé** : Analyse de code existant et correction de bugs logiques et d'interface.
- **Tests Unitaires & d'Intégration** : Utilisation intensive de **Jest** et **Testing Library** pour tester les vues et les conteneurs.
- **Couverture de Code** : Suivi rigoureux des rapports de couverture pour atteindre les objectifs fixés.
- **Chrome DevTools** : Utilisation des outils de développement pour le profilage et le débogage.

---

## ✨ Fonctionnalités clés
- **Authentification** : Gestion des accès pour les rôles Employé et Administrateur.
- **Gestion des Frais** : Création de nouvelles notes de frais avec upload de justificatifs.
- **Validation** : Tableau de bord pour les administrateurs avec visualisation et validation des frais.
- **Responsive Design** : Interface fluide adaptée aux usages bureautiques des RH.

---

## 🚀 Installation et Utilisation

### Prérequis
- **Node.js** (Version 16 ou 18 recommandée)
- **NPM**

### Étape 1 : Lancer le Backend
Le backend utilise une base de données SQLite intégrée.

```bash
cd backend
# Installation des dépendances
npm install
# Lancement du serveur (port 5678)
npm run run:dev
```

### Étape 2 : Lancer le Frontend
```bash
cd frontend
# Installation des dépendances
npm install
# Lancement de l'application
npm install -g live-server
live-server
```
L'application sera accessible sur `http://127.0.0.1:8080/`.

---

## 🧪 Tests
Pour lancer les tests du frontend et voir le rapport de couverture :
```bash
cd frontend
npm run test
```
Le rapport de couverture sera généré dans `frontend/coverage/lcov-report/index.html`.

---

## 🛠️ Structure du Projet
```text
.
├── backend/            # API Node.js & Base de données SQLite
│   ├── controllers/    # Logique métier
│   ├── models/         # Structure des données
│   └── routes/         # Points d'entrée de l'API
├── frontend/           # Application Web (JavaScript Vanille)
│   ├── src/
│   │   ├── containers/ # Logique des composants
│   │   ├── views/      # Templates HTML
│   │   └── __tests__/  # Suites de tests Jest
├── .gitignore          # Configuration Git globale
└── README.md           # Documentation principale
```

---

## 🎓 Contexte Pédagogique
Ce projet est le **11ème et dernier projet** du parcours "Développeur d'Application JavaScript - React" chez OpenClassrooms. Il valide les compétences en débogage, tests automatisés et maintenance de code "legacy".

---

## 👨‍💻 Auteur
**Andréa PORCHE**

- GitHub : [@AndreaP2A](https://github.com/AndreaP2A)
- LinkedIn : [Andrea Porche](https://www.linkedin.com/in/andrea-porche-568b69247/)
- Email : andrea.porche2a@gmail.com
