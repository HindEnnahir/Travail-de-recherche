# Étude de Cas : Système de Gestion des Réservations d'Hôtels (API CRUD)

## Contexte
Cette étude propose de développer et comparer plusieurs technologies pour implémenter un **système de gestion des réservations d'hôtels**. L'API doit permettre les opérations suivantes :

1. **Créer une réservation** : Soumettre des informations client, des dates de séjour et des préférences de chambre.
2. **Consulter une réservation** : Récupérer les détails d'une réservation existante.
3. **Modifier une réservation** : Mettre à jour les informations client et les dates.
4. **Supprimer une réservation** : Annuler une réservation.

Le système doit être performant, scalable, sécurisé et adapté à des environnements multi-utilisateurs et des volumes de données variables.

---

## Objectifs de l'Étude
L'étude a pour but de comparer quatre technologies : **REST**, **SOAP**, **GraphQL** et **gRPC** en se basant sur :

- **Performances** : latence, débit, consommation des ressources.
- **Scalabilité** : capacité à gérer des charges croissantes.
- **Simplicité d'implémentation**.
- **Sécurité** et **flexibilité**.

Des recommandations seront formulées pour identifier la technologie la plus adaptée à divers cas d'usage.

---

## Détails de l'Implémentation

### 1. **Architecture Backend**
Le backend sera développé avec les technologies suivantes :

- **REST** : Implémenté avec **Spring Boot**.
- **SOAP** : Implémenté avec **Spring Boot**.
- **GraphQL** : Utilisation de **Apollo Server**.
- **gRPC** : Utilisation de la **Java gRPC Library**.


## Fonctionnalités de l'API
| Fonctionnalité          | Description                                                   | Endpoint / Opération |
|---------------------------|---------------------------------------------------------------|------------------------|
| **Créer une réservation**  | Ajouter une nouvelle réservation à la base de données.           | POST /reservations     |
| **Consulter une réservation**| Récupérer les détails d'une réservation à partir de son ID.   | GET /reservations/{id} |
| **Modifier une réservation** | Mettre à jour les informations d'une réservation existante.    | PUT /reservations/{id} |
| **Supprimer une réservation**| Annuler une réservation existante à partir de son ID.          | DELETE /reservations/{id} |

---

## Outils et Technologies Utilisés

### Backend
- **Java** avec **Spring Boot** (REST et SOAP)
- **Apollo Server** (GraphQL)
- **Java gRPC Library** (gRPC)


## Comparaison des Résultats
Les performances des quatre technologies seront présentées sous forme de graphiques et de tableaux dans le rapport final. Les critères de comparaison incluent :
- **Temps de réponse** (latence)
- **Ressources consommées**
- **Facilité d'implémentation**
- **Sécurité**
- **Scalabilité**

---

## Résultats Attendues
- Une analyse détaillée des performances de chaque technologie.
- Des recommandations pour choisir la technologie la plus adaptée selon le cas d'usage.

---

