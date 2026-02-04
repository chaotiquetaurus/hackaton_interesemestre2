# hackaton_interesemestre2
Hackaton intersemestre d'informatique quantique de Telecom Paris.

## Setup

soit uv soit (venv + pip) pour l'environement

1. Cloner le repo et se placer dans le dossier :
   ```bash
   git clone git@github.com:chaotiquetaurus/hackaton_interesemestre2.git
   cd hackaton_interesemestre2
   ```

2. Installer graphviz (dependance systeme) :
   ```bash
   sudo apt install graphviz
   ```

3. Creer le virtual environment et installer les dependances :
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install .
   ```

4. Lancer Jupyter Notebook :
   ```bash
   jupyter notebook
   ```



#### installer uv (gestionnaire de paquet python)
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```
#### syncroniser l'environement (grace au .toml et .lock)
```bash
uv sync
```

### soit ouvrir dans VSCode soit dans un serveur jupyter
```bash
uv run --with jupyter jupyter lab
```
