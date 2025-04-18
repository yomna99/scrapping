# scrapping
# 📖 Archive Numérique - Jacques Chirac


## 📋 Table des matières
- [Objectif du Projet](#🎯-objectif-du-projet)
- [Fonctionnalités](#✨-fonctionnalités)
- [Technologies Utilisées](#🛠️-technologies-utilisées)
- [Installation](#🔧-installation)
- [Utilisation](#🚀-utilisation)
- [Structure des Données](#🗂️-structure-des-données)
- [Exemples](#🔍-exemples)


## 🎯 Objectif du Projet
Ce projet permet de collecter, structurer et archiver automatiquement les publications en ligne concernant le décès de Jacques Chirac, ancien Président français. L'archive créée sert de base pour :
- La recherche historique
- L'analyse médiatique
- La préservation numérique des hommages

## ✨ Fonctionnalités
- **Scraping intelligent** des plateformes en ligne
- **Nettoyage automatique** des données
- **Stockage sécurisé** dans MongoDB Atlas
- **Recherche optimisée** grâce aux index
- **Gestion des métadonnées** complète

## 🛠️ Technologies Utilisées
| Catégorie       | Technologies                          |
|----------------|--------------------------------------|
| Scraping       | Python, Selenium, BeautifulSoup      |
| Base de données| MongoDB Atlas                        |
| Sécurité       | TLS, dotenv                          |
| Infrastructure | Git, GitHub                          |

## 🔧 Installation
1. **Cloner le dépôt**
```bash
git clone https://github.com/votre-utilisateur/archivage-chirac.git
cd archivage-chirac

# 🗃️ Archive Numérique - Jacques Chirac

![Interface MongoDB dans Atlas](assets/mongodb_view.png)
*Capture de l'interface MongoDB  montrant les données enregistrées*

## 📊 Structure des Données dans MongoDB

### 1. Schéma des Documents
Chaque publication est stockée sous ce format dans la collection `publications` :

```json
{
  "_id": ObjectId("6512d8f1a2b5c44d5f8e3a21"),
  "text": "Décès de Jacques Chirac à 86 ans. L'ancien président...",
  "image": {"https://example.com/chirac1.jpg"},
  "source" : "facebook"
"import_date" : 2025-04-18T20:24:33.814+00:00
  },
  
