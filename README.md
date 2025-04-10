# 📘 Projet Base de Données - Gestion Hôtelière

## 📌 Objectif
Ce projet a pour but de modéliser et concevoir une base de données relationnelle permettant de gérer les informations liées aux hôtels, aux chambres, aux employés, et à leurs caractéristiques.

---

## 📐 Modélisation

### ✅ Modèle Entité-Association
Le modèle entité-association comporte les entités suivantes :
- **Hotel**
- **Type** (type d’hôtel : luxe, économique, etc.)
- **Room** (chambre)
- **Category** (catégorie de chambre)
- **Employee**

Les relations sont :
- Un hôtel **est** d’un type.
- Un hôtel **est composé** de plusieurs chambres.
- Une chambre **est de** une catégorie.
- Un employé **travaille** dans un hôtel.
- Un employé **dirige** (leads) d'autres employés.

---

## 🧩 Diagramme Relationnel

Voici le schéma relationnel issu de la conversion du modèle entité-association :

