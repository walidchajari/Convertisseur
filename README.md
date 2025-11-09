

## ** Convertisseur (Flask App)**

```markdown
# 💱 Convertisseur de Devises – Application Flask

## 📝 Présentation

**Convertisseur** est une application web interactive développée en **Python (Flask)** permettant de convertir des devises entre le **MAD**, **USD**, **EUR** et **GBP**.  
Elle simule des **taux de change dynamiques**, affiche des **tendances historiques** et présente une interface moderne grâce à **HTML, CSS et JavaScript**.

---

## 🚀 Fonctionnalités principales

- 💰 Conversion instantanée entre MAD, USD, EUR, GBP  
- 📈 Génération de données historiques simulées sur 7 jours  
- 🔍 Analyse automatique de tendance (hausse, baisse, stable)  
- 🎨 Interface web responsive et intuitive  
- 🧩 Code clair et extensible (API Flask + JS Frontend)

---

## 🧱 Architecture du projet

```

Convertisseur/
├── app.py                 # Application Flask principale
├── static/
│   ├── styles.css         # Feuille de style principale
│   ├── converter.js       # Logique de conversion côté client
│   ├── main.js            # Scripts additionnels
│   └── ...
├── templates/             # (si existant) Templates HTML
├── .venv/                 # Environnement virtuel Python
└── logs/                  # Journaux d’exécution (flask.log, app_run.log)

````

---

## ⚙️ Installation et exécution

### 1️⃣ Cloner le dépôt
```bash
git clone https://github.com/ton-utilisateur/Convertisseur.git
cd Convertisseur/Convestisseur
````

### 2️⃣ Créer un environnement virtuel

```bash
python -m venv .venv
source .venv/bin/activate  # Linux/Mac
.venv\Scripts\activate     # Windows
```

### 3️⃣ Installer les dépendances

```bash
pip install flask
```

### 4️⃣ Lancer l’application

```bash
python app.py
```

Puis ouvrir [http://127.0.0.1:5000](http://127.0.0.1:5000) dans ton navigateur.

---

## 🧠 Utilisation

L’interface te permet de :

* Sélectionner la **devise source et cible**
* Entrer un montant
* Visualiser la **conversion instantanée**
* Observer les **variations de taux sur la semaine**

Exemple de route Flask :

```python
@app.route("/")
def index():
    return render_template("index.html")
```

---

## 🧰 Technologies utilisées

* **Backend :** Python 3.13, Flask
* **Frontend :** HTML5, CSS3, JavaScript
* **Outils :** Virtualenv, Jinja2, Random, Datetime

---

## 👨‍💻 Auteur

Projet développé par **Funny Ch (@onjarw)**
📧 Contact : [onjarw@gmail.com](mailto:onjarw@gmail.com)

---

## 📜 Licence

Ce projet est distribué sous licence **MIT**.
Libre d’utilisation, de modification et de distribution.

````

---

## 🇬🇧 **README – Currency Converter (Flask App)**

```markdown
# 💱 Currency Converter – Flask Web Application

## 📝 Overview

**Convertisseur** is a lightweight and interactive **Flask web application** built in **Python**, designed to convert currencies between **MAD**, **USD**, **EUR**, and **GBP**.  
It generates **simulated exchange rates** and displays **7-day historical trends** with a clean and responsive interface.

---

## 🚀 Key Features

- 💰 Real-time currency conversion (MAD, USD, EUR, GBP)  
- 📈 Simulated 7-day historical exchange rate data  
- 🔍 Automatic trend analysis (up, down, stable)  
- 🎨 Responsive user interface with HTML/CSS/JS  
- 🧩 Modular and maintainable Flask architecture  

---

## 🧱 Project Structure

````

Convertisseur/
├── app.py                 # Main Flask app
├── static/
│   ├── styles.css         # Styling
│   ├── converter.js       # Client-side conversion logic
│   ├── main.js            # Front-end scripts
│   └── ...
├── templates/             # HTML templates (if any)
├── .venv/                 # Virtual environment
└── logs/                  # Execution logs (flask.log, app_run.log)

````

---

## ⚙️ Installation & Run

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/Convertisseur.git
cd Convertisseur/Convestisseur
````

### 2️⃣ Create a virtual environment

```bash
python -m venv .venv
source .venv/bin/activate  # Linux/Mac
.venv\Scripts\activate     # Windows
```

### 3️⃣ Install dependencies

```bash
pip install flask
```

### 4️⃣ Run the app

```bash
python app.py
```

Visit [http://127.0.0.1:5000](http://127.0.0.1:5000) in your browser.

---

## 🧠 Usage

The app allows you to:

* Select source and target currencies
* Enter an amount to convert
* View instant conversion and weekly rate trend

Example Flask route:

```python
@app.route("/")
def index():
    return render_template("index.html")
```

---

## 🧰 Technologies Used

* **Backend:** Python 3.13, Flask
* **Frontend:** HTML5, CSS3, JavaScript
* **Utilities:** Virtualenv, Jinja2, Datetime, Random

---

## 👨‍💻 Author

Developed by **Funny Ch (@onjarw)**
📧 Contact: [walidchajari02@gmail.com](mailto:onjarw@gmail.com)

---

## 📜 License

This project is released under the **MIT License**.
You are free to use, modify, and distribute it.

```

---

Souhaites-tu que je te crée ces deux README directement sous forme de **fichiers prêts à télécharger (`README_FR.md` et `README_EN.md`)** ?
```
