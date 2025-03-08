# AnalyseDonneeTitanic

# Cloner le dépôt
git clone https://github.com/dinho11701/AnalyseDonneeTitanic.git
cd AnalyseDonneeTitanic

# Créer et activer l'environnement virtuel
python3 -m venv mon_env
source mon_env/bin/activate   # macOS/Linux
mon_env\Scripts\activate      # Windows

# Installer les dépendances
pip install --upgrade pip
pip install -r requirements.txt  # Si vous avez un fichier requirements.txt

# Lancer Jupyter Notebook
jupyter notebook

# Ajouter le noyau pour l'environnement virtuel
python -m ipykernel install --user --name=mon_env --display-name "Python (mon_env)"

# Dans Jupyter, sélectionnez le noyau "Python (mon_env)"

# Désactiver l'environnement virtuel après utilisation
deactivate

