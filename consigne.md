# Pawcalypse Now : Le Soulèvement des Chats 🐾

Les chats, fatigués d’être confinés au rôle de simples animaux de compagnie, se préparent à prendre le contrôle de la planète. Organisés, stratégiques, et dotés d’un humour noir, ils vous engagent pour développer leur plateforme de commandement numérique. Préparez-vous à coder pour le plus grand soulèvement félin de l'histoire : **Pawcalypse Now !** 🐾

---

## Étape 1 : Initialisation du Projet

### Création du Dépôt Git :
1. Créez un dépôt sur **GitLab** ou **GitHub** pour héberger votre projet.
2. Clonez ce dépôt sur votre machine locale.
3. Créez une branche de développement (`develop`) pour séparer les modifications de la branche principale.

### Configuration Docker :
1. Créez un fichier `Dockerfile` et un fichier `docker-compose.yml` pour configurer un environnement PHP et MySQL.
   - **Dockerfile** : Définit l’image PHP et installe les extensions nécessaires (ex., PDO pour MySQL).
   - **docker-compose.yml** : Orchestration des services (web et base de données).

### Vérification de l'environnement :
1. Assurez-vous que le serveur PHP démarre correctement.
2. Validez l'accès à la base de données MySQL.

---

## Étape 2 : Création de la Base de Données

### Conception de la Base de Données MySQL :
- Créez une base de données `catworlddb` contenant les tables suivantes :
  - **`users`** : Gère les informations de connexion des utilisateurs.
  - **`resources`** : Stocke le "stock mondial de croquettes" et l'"herbe à chat".
  - **`conquest_plans`** : Enregistre les plans de "conquête du monde", incluant :
    - Pourcentage de progression.
    - Invasions planifiées.

### Tables Supplémentaires :
1. **`missions`** : Missions associées à chaque plan de conquête (en cours, planifiées, terminées).
2. **`resource_usage`** : Suivi de l’utilisation des ressources par mission.
3. **`achievements`** : Succès ou accomplissements pour chaque mission.

### Alimentation en Données Fictives :
- Ajoutez des données humoristiques :
  - **`users`** : Chats stratèges pouvant se connecter.
  - **`resources`** : Quantités fictives de croquettes et herbe à chat.
  - **`conquest_plans`** : Plans de conquête et missions associées.

---

## Étape 3 : Implémentation de la Fonctionnalité de Connexion

### Création du Formulaire de Connexion :
1. Développez un formulaire PHP permettant aux utilisateurs de se connecter.
2. Utilisez des **sessions** pour gérer l’authentification.

### Gestion des Messages :
- **Messages d’erreur** : Identifiants incorrects ou champs vides.
- **Messages de succès** : Connexion réussie.

---

## Étape 4 : Création du Tableau de Bord

### Conception de l’Interface :
- Créez une page `dashboard.php`, accessible uniquement aux utilisateurs connectés.
- Affichez des informations fictives, comme :
  - Pourcentage de conquête mondiale.
  - Stocks de croquettes et herbe à chat.
  - Liste des invasions planifiées.

### Affichage Dynamique des Données :
- Utilisez des requêtes SQL pour récupérer les informations de la base de données.
- Appliquez une mise en page en CSS pour améliorer la présentation.

---

## Étape 5 : Mise en Place des Fonctionnalités Avancées et Sécurisation

### Fonctionnalité de Mise à Jour :
1. Ajoutez une interface permettant de :
   - Lancer une invasion en modifiant les données de `conquest_plans`.
   - Mettre à jour les quantités de ressources disponibles.

### Sécurisation :
1. Utilisez des **requêtes préparées** pour éviter les injections SQL.
2. Validez toutes les entrées utilisateur pour garantir l’intégrité des données.

---

## Étape 6 : Documentation et Préparation pour le Déploiement

### Documentation du Code :
- Ajoutez des commentaires explicatifs dans le code (connexion, requêtes SQL, sessions).

### Guide de Déploiement :
- Créez un fichier `README.md` pour expliquer :
  1. Comment cloner le dépôt.
  2. Configurer Docker pour le projet.
  3. Lancer le site.

### Tests Finaux :
1. Vérifiez toutes les fonctionnalités (connexion, tableau de bord, mise à jour des données).
2. Assurez-vous de la stabilité et de l'ergonomie du site.

---

## Étape 7 : Livraison et Soumission

### Finalisation :
1. Effectuez une dernière vérification du code et de la documentation.
2. Assurez-vous que toutes les dépendances sont incluses dans le dépôt.

### Soumission sur Moodle :
- Publiez le lien de votre dépôt **GitLab**/**GitHub** sur Moodle.
- Assurez-vous que le dépôt contient :
  - Docker.
  - Documentation.
  - Code fonctionnel.

--- 

Bonne chance pour le plus grand soulèvement félin de l'histoire ! 🐾
