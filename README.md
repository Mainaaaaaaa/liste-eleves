# Liste des élèves

Application Flask qui affiche la liste des élèves de la promo.

## Installation

```bash
# Créer l'environnement virtuel
python -m venv .venv

# L'activer
# Sur Mac/Linux :
source .venv/bin/activate
# Sur Windows :
.venv\Scripts\activate

# Installer les dépendances
pip install -r requirements.txt
```

## Lancer l'application

```bash
python app.py
```

Ouvrir http://localhost:5000 dans le navigateur.

## Ajouter votre nom

Dans `app.py`, repérez la liste `eleves` et ajoutez votre ligne :

```python
eleves = [
    {"prenom": "Loïc", "nom": "Dumont", "github": "loic-prof"},
    {"prenom": "Votre prénom", "nom": "Votre nom", "github": "votre-username"},
]
```
