# Architectures Web 3-Tiers et MVC avec Struts, Spring et Java

🔗 **Document associé :**
[Architectures à 3 couches et architectures MVC avec Struts, Spring et Java](https://stahe.github.io/java-web3tier-mars-2005/)

---

## 📘 Présentation

Ce dépôt regroupe le contenu de deux articles publiés entre mars et juillet 2005 sur Developpez.com.
Ils abordent les architectures web Java selon une approche pédagogique et progressive :

1. **Spring IoC**
   Introduction à l’**Inversion of Control (IoC)**, également appelée **Injection de Dépendances (DI)**, à travers le framework Spring.

2. **Trois exemples d’architecture web à trois couches**
   Présentation d’une application web simplifiée de gestion d’achats en ligne, implémentée selon une architecture **MVC (Model–View–Controller)** et déclinée en trois variantes techniques.

---

## 🏗️ Architectures abordées

L’application exemple est structurée selon une architecture **3-tiers** :

* **Couche Présentation (View)**
* **Couche Métier (Business Logic)**
* **Couche Accès aux Données (Data Access)**

Le modèle **MVC** est implémenté de trois manières différentes :

### 1️⃣ Servlet + JSP

* Une **servlet contrôleur**
* Des **pages JSP** pour les vues
* Architecture MVC manuelle

### 2️⃣ Struts

* Implémentation MVC basée sur le framework **Struts**
* Centralisation du contrôle via `ActionServlet`
* Mapping déclaratif des actions

### 3️⃣ Spring MVC

* Utilisation du framework **Spring MVC**
* Intégration avec le conteneur IoC de Spring
* Configuration orientée injection de dépendances

---

## 🎯 Objectifs pédagogiques

* Comprendre le principe d’**architecture 3 couches**
* Maîtriser le modèle **MVC en environnement Java Web**
* Découvrir l’**Inversion of Contrôle (IoC)** et l’Injection de Dépendances
* Comparer différentes approches d’implémentation MVC
* Appréhender les apports des frameworks par rapport à une implémentation manuelle

---

## 🧩 Technologies utilisées

* Java
* Servlets
* JSP
* Struts
* Spring Framework
* Spring MVC

---

## 📚 Public cible

Ce support s’adresse :

* Aux développeurs Java souhaitant comprendre les architectures web classiques
* À toute personne souhaitant comparer MVC “manuel” et MVC frameworkisé

---

## 🏷️ Contexte historique

Ces articles datent de 2005 et reflètent l’état des pratiques Java Web de l’époque.

