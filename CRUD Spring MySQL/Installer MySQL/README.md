# Installer MySQL et Créer une Base de Données

Dans ce tutoriel, nous allons apprendre à installer **MySQL** sur Windows et à créer une base de données appelée `product_db`, que nous utiliserons plus tard pour un projet **CRUD** avec **Spring Boot**. Suivez ces étapes avant de passer à la configuration de Spring Boot dans la prochaine vidéo.

---

## 1. Télécharger et Installer MySQL

### A. Télécharger MySQL

1. Rendez-vous sur le site officiel de MySQL : [Télécharger MySQL](https://dev.mysql.com/downloads/installer/).
2. Choisissez **MySQL Installer for Windows**.
3. Téléchargez le fichier en cliquant sur "No thanks, just start my download".

### B. Installer MySQL

1. Double-cliquez sur le fichier téléchargé pour lancer l’installation.
2. Choisissez les composants à installer : sélectionnez **MySQL Server** et **MySQL Workbench**.
3. Définissez un mot de passe fort pour le compte **root** pendant l’installation.

---

## 2. Configurer MySQL et Créer une Base de Données

### A. Démarrer MySQL

1. Une fois l’installation terminée, démarrez **MySQL Server** via **MySQL Workbench**.
2. Connectez-vous avec le compte **root** et le mot de passe défini pendant l’installation.

### B. Créer la Base de Données `product_db`

1. Ouvrez un nouvel onglet de requêtes dans **MySQL Workbench**.
2. Tapez la commande suivante pour créer la base de données `product_db` :
   ```sql
   CREATE DATABASE product_db;
   ```
3. Pour vérifier que la base de données a bien été créée, exécutez la commande suivante :
   ```sql
   SHOW DATABASES;
   ```
   Vous devriez voir `product_db` dans la liste des bases de données.

---

## 3. Liens Utiles

- [Télécharger MySQL](https://dev.mysql.com/downloads/installer/)
- [Documentation MySQL](https://dev.mysql.com/doc/)

---

## 4. Vidéo Associée

Consultez la vidéo associée sur YouTube pour une démonstration complète du processus d'installation et de création de la base de données.

---

## 5. Étape Suivante

Dans la prochaine vidéo, nous verrons comment connecter cette base de données à un projet **Spring Boot** pour créer une application CRUD complète. Restez connecté et n’oubliez pas de vous abonner pour la suite !
