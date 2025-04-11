
# 🔬 Application de Prédiction du Stade de l'Insuffisance Rénale Chronique (IRC)

Ce projet fullstack permet de prédire le stade de l'Insuffisance Rénale Chronique (IRC) à partir de données cliniques et biologiques.  
Il utilise **FastAPI** pour le backend et **Streamlit** pour le frontend, avec un modèle de machine learning basé sur **Scikit-learn** et le modèle **Random Forest** pour la prédiction.

## 📂 Structure du projet

```
app-irc-fullstack/
├── backend/         # Code backend (API FastAPI)
├── frontend/        # Interface utilisateur (Streamlit)
├── README.md        # Ce fichier

```

## 🚀 Liens déployés

- 🔗 [Interface utilisateur (Streamlit)](https://frontend-xi4d.onrender.com/)
- ⚙️ [API backend (FastAPI)](https://backend-ta25.onrender.com)

## ▶️ Utilisation

1. **Ouvrir l'interface utilisateur via le lien ci-dessus**.
2. **Remplir les informations du patient** dans le formulaire.
3. **Cliquer sur "Prédire le Stade de l'IRC"** pour obtenir la prédiction du stade.
4. **Le résultat et des conseils sur le traitement** s'affichent automatiquement après la prédiction.

## 🛠️ Technologies utilisées

- **Python** : Langage de programmation principal.
- **FastAPI** : Framework rapide pour l'API backend.
- **Streamlit** : Outil pour construire une interface utilisateur interactive.
- **Scikit-learn** : Bibliothèque pour l'implémentation du modèle de machine learning.
- **Render** : Plateforme d'hébergement pour le déploiement du frontend et du backend.

## 📋 Prérequis

Avant de commencer, assurez-vous d'avoir les éléments suivants installés sur votre machine :

- Python 3.11 ou supérieur
- Pip (pour l'installation des dépendances)

## ▶️ Installation et lancement en local

### Cloner le projet avec les sous-modules

Pour cloner ce projet avec ses sous-modules (backend et frontend), exécutez la commande suivante :

```bash
git clone --recurse-submodules https://github.com/Michel1904/app-irc-fullstack.git
```

### Installer les dépendances

Accédez au dossier du projet et installez les dépendances nécessaires pour le backend et le frontend :

```bash
cd app-irc-fullstack
# Backend
cd backend
pip install -r requirements.txt
cd ..

# Frontend
cd frontend
pip install -r requirements.txt
cd ..
```

### Lancer le projet

#### Backend (FastAPI) :

Lancez le serveur backend avec la commande suivante :

```bash
cd backend
uvicorn main:app --reload
```

Le backend sera accessible à l'adresse `http://127.0.0.1:8000`.

#### Frontend (Streamlit) :

Lancez l'interface utilisateur avec Streamlit :

```bash
cd frontend
streamlit run app.py
```

L'interface sera accessible à l'adresse `http://localhost:8501`.

## 🧑‍💻 Déploiement

Pour déployer cette application en ligne, nous avons utilisé **Render** pour héberger à la fois le backend et le frontend.

- Le backend FastAPI est déployé sur Render à l'adresse [backend-ta25.onrender.com](https://backend-ta25.onrender.com).
- Le frontend Streamlit est déployé à l'adresse [frontend-xi4d.onrender.com/](https://frontend-xi4d.onrender.com/).

### Explication du fichier README :

1. **Introduction claire** sur le but du projet et les technologies utilisées.
2. **Structure du projet** pour aider à comprendre l'organisation des dossiers.
3. **Liens déployés** pour l'accès rapide à l'interface et à l'API.
4. **Instructions d'utilisation** détaillées pour l'utilisateur final.
5. **Prérequis** et **installation en local** pour ceux qui souhaitent tester le projet localement.
6. **Déploiement** pour ceux qui souhaitent comprendre comment le projet a été mis en ligne.
7. **Crédits** et **licence** pour donner la reconnaissance appropriée et préciser la licence d'utilisation.

Il te suffit de copier ce contenu dans un fichier `README.md` et de le pousser sur ton dépôt GitHub. Cela donnera une documentation claire et professionnelle à ton projet !
