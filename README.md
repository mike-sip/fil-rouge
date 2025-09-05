# 🚀 Projet fil rouge : Plateforme de gestion de projets collaboratifs ("TaskFlow")

## 📌 Description
Développer une application web qui permet à des utilisateurs de s’inscrire, créer des projets, inviter des collaborateurs et gérer des tâches avec suivi en temps réel.

---

## 📚 Étapes d’apprentissage et aspects de Spring Boot couverts

### 1. Bases et REST API
- Créer un projet Spring Boot avec **Spring Initializr**.  
- Mettre en place les entités de base : `User`, `Project`, `Task`.  
- Créer des **endpoints REST** avec `@RestController` (CRUD sur les entités).  
- Utiliser **DTOs et MapStruct** pour séparer la couche API de la couche persistance.  

👉 Tu apprends : structure d’un projet, REST controllers, JSON (Jackson).  

---

### 2. Persistance et base de données
- Configurer une base de données relationnelle (PostgreSQL ou MySQL).  
- Utiliser **Spring Data JPA** pour gérer les entités.  
- Mettre en place des relations (`OneToMany`, `ManyToMany`).  
- Gérer les **requêtes personnalisées** avec `@Query` et `Specification`.  
- Ajouter **Flyway ou Liquibase** pour la migration de schéma.  

👉 Tu apprends : JPA, Hibernate, migrations DB, bonnes pratiques persistance.  

---

### 3. Sécurité et authentification
- Implémenter l’authentification avec **Spring Security**.  
- Mettre en place le login avec **JWT**.  
- Gérer les rôles : `USER`, `ADMIN`.  
- Restreindre l’accès aux endpoints avec `@PreAuthorize`.  

👉 Tu apprends : sécurité, JWT, gestion des rôles.  

---

### 4. Services avancés
- Ajouter un **système de notifications** (par email via Spring Mail).  
- Implémenter une **API de recherche** sur les tâches (critères multiples).  
- Intégrer un **scheduler** (Spring Scheduling) pour envoyer des rappels automatiques.  
- Ajouter un **upload de fichiers** (pièces jointes sur les tâches).  

👉 Tu apprends : services asynchrones, email, scheduling, gestion des fichiers.  

---

### 5. Temps réel et communication
- Intégrer **WebSocket avec STOMP** pour des notifications temps réel (ex : quand une tâche est modifiée).  
- Mettre en place un **chat simple** entre membres d’un projet.  

👉 Tu apprends : WebSocket, STOMP, messagerie temps réel.  

---

### 6. Tests et qualité
- Écrire des **tests unitaires** (JUnit 5, Mockito).  
- Créer des **tests d’intégration** avec `@SpringBootTest`.  
- Ajouter des tests sur les controllers avec `MockMvc`.  
- Mesurer la couverture avec **JaCoCo**.  

👉 Tu apprends : tests unitaires/intégration, TDD possible.  

---

### 7. Observabilité et monitoring
- Intégrer **Spring Actuator** pour exposer les métriques.  
- Ajouter **Micrometer + Prometheus** pour la supervision.  
- Visualiser avec **Grafana**.  

👉 Tu apprends : monitoring, métriques, observabilité.  

---

### 8. Déploiement et industrialisation
- Conteneuriser avec **Docker**.  
- Écrire un **Docker Compose** avec PostgreSQL + ton app.  
- Déployer sur **Heroku / Render / Railway** ou un serveur perso.  
- Ajouter un **CI/CD simple** avec GitHub Actions.  

👉 Tu apprends : DevOps de base, CI/CD, déploiement cloud.  

---

## ✅ Objectif final
À la fin, tu auras une **application complète, sécurisée, scalable et monitorée**, et tu auras exploré presque tout ce que propose Spring Boot.
