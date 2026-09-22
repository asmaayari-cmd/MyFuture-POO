# MyFuture Core Engine — Projet Fil Rouge POO (Java)

![Java](https://img.shields.io/badge/Java-21-orange.svg)
![IDE](https://img.shields.io/badge/IDE-Visual%20Studio%20%2F%20VS%20Code-blue.svg)
![Course](https://img.shields.io/badge/Module-Programmation%20Orient%C3%A9e%20Objet-green.svg)
![Institution](https://img.shields.io/badge/ISET'Com-2026--2027-brightgreen.svg)

Bienvenue dans le dépôt officiel du projet **MyFuture Core**, le projet fil rouge et la Situation d'Apprentissage et d'Évaluation (SAE) du cours de **Programmation Orientée Objet (Java)** à l'ISET'Com.

---

## À Propos du Projet MyFuture

**MyFuture** est une plateforme numérique d'accompagnement intelligent vers l'emploi. Elle permet aux étudiants de gérer leur profil professionnel, d'analyser l'écart de compétences (*Skill Gap Analysis*) par rapport à un métier cible, de gérer un portfolio de projets et de bénéficier d'un moteur de recommandation d'offres de stages et d'emplois.

---

## Structure du Dépôt

```text
MyFuture-POO/
├── .vscode/                 # Configuration Visual Studio / VS Code (launch.json)
├── src/                     # Code source Java
│   └── com/
│       └── myfuture/
│           ├── core/        # Moteur principal et classes de démarrage (MyFutureMain)
│           └── model/       # Modèles du domaine (Personne, Etudiant, Enseignant, etc.)
├── bin/                     # Fichiers compilés (.class) — généré automatiquement
├── doc/                     # Documentation technique générée (Javadoc)
├── .gitignore               # Exclusion des fichiers temporaires/compilés
└── README.md                # Documentation principale du dépôt
```

---
## Guide Démarrage Rapide

### 1. Cloner le Dépôt
```bash
git clone https://github.com/votre-compte/MyFuture-POO.git
cd MyFuture-POO
```

### 2. Exécution dans Visual Studio / VS Code
* Ouvrez le dossier du projet dans l'IDE (`Fichier > Ouvrir le dossier`).
* Ouvrez le fichier `src/com/myfuture/core/MyFutureMain.java`.
* Appuyez sur la touche **`F5`** ou cliquez sur le bouton **`Run`** situé au-dessus de la méthode `main()`.

### 3. Exécution depuis le Terminal
```bash
# Compilation
javac -d bin src/com/myfuture/core/MyFutureMain.java

# Exécution avec arguments
java -cp bin com.myfuture.core.MyFutureMain --mode=DEV --user=Etudiant-GTIC
```

---
## Directives de Git & Soumission des Travaux

Pour chaque TP, vous devez valider vos modifications avec des messages de commit clairs et structurés :

```bash
# 1. Vérifier les fichiers modifiés
git status

# 2. Ajouter les fichiers au staging
git add .

# 3. Effectuer le commit correspondant au TP
git commit -m "TP X : [Brève description de la fonctionnalité ajoutée]"

# 4. Synchroniser avec GitHub
git push origin main
```

---
