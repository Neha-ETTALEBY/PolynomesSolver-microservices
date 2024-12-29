# **Résolution d'Équations Polynômiales avec une Architecture Microservices**

Ce projet vise à fournir une solution modulaire et extensible pour résoudre des équations polynomiales à l'aide d'une architecture basée sur les microservices. Le système intègre des technologies modernes comme *Spring Boot*, *React*, et *Flutter* pour garantir performance et adaptabilité.

---

## **Table des Matières**
- [Description du Projet](#description-du-projet)
- [Technologies Utilisées](#technologies-utilisées)
- [Architecture](#architecture)
- [Fonctionnalités](#fonctionnalités)
- [Installation](#installation)
- [Utilisation](#utilisation)
- [Exemples Illustratifs](#exemples-illustratifs)
- [Contributeurs](#contributeurs)
- [Licence](#licence)

---

## **Description du Projet**

Cette application résout des équations polynomiales en utilisant des méthodes analytiques et numériques. Elle est conçue pour être scalable, modulaire, et capable d'intégrer facilement de nouvelles fonctionnalités. Deux types de méthodes sont prises en charge :

- **Méthodes Numériques** : Approches comme les formules de Cardan et Ferrari.
- **Méthodes Analytiques** : Techniques telles que Newton-Raphson et la méthode de bisection.

---

## **Technologies Utilisées**

- **Frontend** : React, Flutter
- **Backend** : Spring Boot avec Spring Cloud Gateway
- **Service Discovery** : Netflix Eureka
- **Base de Données** : MySQL

---

## **Architecture**

L'application est divisée en plusieurs composants :

- **Client REST API** : Les frontends envoient des requêtes utilisateur au backend.
- **Passerelle** : Spring Cloud Gateway route les requêtes vers les microservices appropriés.
- **Microservices** : Services indépendants pour traiter des tâches spécifiques.
- **Service Discovery** : Netflix Eureka pour la découverte dynamique des microservices.

![Architecture des services]([[https://github.com/user-attachments/assets/6155df5a-5d46-421a-81cf-31c5b66fde12](https://app.eraser.io/workspace/ckNFDmpsj8GlPOET39RP?origin=share](https://app.eraser.io/workspace/ckNFDmpsj8GlPOET39RP)))

---

## **Fonctionnalit\u00e9s**

- **Calcul des racines** : Trouver les solutions d'un polyn\u00f4me.
- **Factorisation** : Diviser les polyn\u00f4mes en facteurs.
- **Calcul par la m\u00e9thode de Newton** : Approximation des solutions analytiques.
- **Calcul quadratique** : R\u00e9solution des polyn\u00f4mes du second degr\u00e9.
- **Visualisation graphique** : Repr\u00e9sentation graphique des polyn\u00f4mes et de leurs racines.

---

## **Installation**

### **Backend**
1. Cloner ce dépôt :
   ```bash
   git clone https://github.com/Neha-ETTALEBY/PolynomesSolver-microservices.git
   ```
2. Naviguer dans le répertoire backend et lancer les services :
   ```bash
   cd CalculPolynome-backend
   mvn clean install
   mvn spring-boot:run
   ```

### **Frontend React**
1. Aller dans le répertoire React :
   ```bash
   cd polynome_front_react
   ```
2. Installer les dépendances :
   ```bash
   npm install
   ```
3. Lancer le serveur de développement :
   ```bash
   npm start
   ```

### **Frontend Flutter**
1. Naviguer dans le répertoire Flutter :
   ```bash
   cd polynome_front_flutter
   ```
2. Vérifier l'installation de Flutter :
   ```bash
   flutter doctor
   ```
3. Lancer l'application :
   ```bash
   flutter run
   ```

---

## **Utilisation**

1. Accédez à l'interface utilisateur via `http://localhost:3000` pour React ou `http://localhost:8088` pour Flutter.
2. Saisissez une équation polynomiale et sélectionnez la méthode de résolution souhaitée.
3. Consultez les résultats affichés sur l'interface.

---

## **Exemples Illustratifs**

### Exemple 1 : Résolution d'un polynôme 
**Polynôme :** `x² - 5x + 6 = 0`  
**Résultat :** `x = 2, x = 3`

---

## **Vidéo Démonstrative**

- [Démonstration Backend & Frontend](https://github.com/user-attachments/assets/52c34e39-b6e8-420a-af23-55b1330a4ec2)
- [Démonstration Mobile Flutter](https://github.com/user-attachments/assets/68736cf1-891f-4c27-a825-03b8cb6e1e44)

---

## **Contributeurs**

- **Maria GUERMOUD**
- **Aya ELFAHIMI**
- **Douaa ELFAHIMI**
- **Aziza ATIGUI**

---

## **Licence**

Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.
