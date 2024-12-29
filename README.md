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

![Architecture des services](https://github.com/user-attachments/assets/6155df5a-5d46-421a-81cf-31c5b66fde12)

---

## **Fonctionnalités**

- Résolution de polynômes par degré (quadratiques, cubiques, quartiques, etc.).
- Approximation des racines via des méthodes analytiques.
- Routage intelligent des requêtes via la passerelle.
- Microservices spécialisés pour chaque fonction du projet.

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

### Exemple 1 : Résolution d'un polynôme quadratique
**Polynôme :** `x² - 5x + 6 = 0`  
**Résultat :** `x = 2, x = 3`

---

## **Vidéo Démonstrative**

- [Démonstration Backend & Frontend](https://github.com/user-attachments/assets/6e781dda-6457-4a27-8ae5-c62f4d223c9d)
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
