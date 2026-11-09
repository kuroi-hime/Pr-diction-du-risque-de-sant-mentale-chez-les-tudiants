# Pr-diction-du-risque-de-sant-mentale-chez-les-tudiants
Le projet vise à analyser un jeu de données afin de classifier et d’étudier les  facteurs associés au bien-être et au risque de santé mentale des étudiants. Le projet couvre toute la chaîne Data Science : audit, nettoyage, EDA, feature 
engineering, preprocessing, entraînement, optimisation, évaluation, automatisation et visualisation. 
Le modèle ne doit jamais être présenté comme un outil de diagnostic, de décision disciplinaire ou de sélection d’étudiants. 


## Instructions
### 1. Création d’un environnement virtuel
Exécuter la commande suivante dans le terminal :
```cmd
python -m venv <nom_environnement>
```
Remplacer <nom_environnement> par le nom souhaité, par exemple venv ou .venv.

### 2. Activation de l’environnement virtuel
Avec CMD :
```cmd
<nom_environnement>\Scripts\activate.bat
```
Avec PowerShell :
```powershell
.\<nom_environnement>\Scripts\Activate.ps1
```
Cette activation concerne la plateforme Windows, vous pouvez consulter la votre sur [Activation selon plateforme](https://docs.python.org/fr/3/library/venv.html).

### 3. Vérification de l’activation
Une fois l’environnement activé, son nom apparaît généralement au début de la ligne de commande, par exemple :
```text
(venv) C:\mon_projet>
```
Pour vérifier quel interpréteur Python est utilisé :
```bash
python -c "import sys; print(sys.executable)"
```