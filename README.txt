Lynx Browser - README

Description :
Lynx Browser est un navigateur simple et léger développé en Python avec PyQt5. Il permet de naviguer sur Internet via une interface basique mais fonctionnelle. Vous pouvez ouvrir plusieurs onglets, revenir à la page d'accueil, naviguer avant/arrière, et recharger les pages. 

Fonctionnalités :
- Navigation par onglets (plusieurs onglets peuvent être ouverts en même temps)
- Barre d'adresse pour entrer une URL
- Boutons pour revenir à la page d'accueil, naviguer en avant et en arrière, et recharger la page
- Fermeture des onglets via un bouton sur chaque onglet
- Icône personnalisée pour l'application

Prérequis :
- Python 3.x
- PyQt5
- PyQtWebEngine

Installation :
1. Clonez ou téléchargez le projet.
2. Installez les dépendances avec la commande suivante :
   pip install -r requirements.txt
3. Exécutez le fichier app.py avec la commande :
   python app.py

Créer un fichier .exe :
1. Installez PyInstaller si ce n'est pas déjà fait :
   pip install pyinstaller
2. Pour générer le fichier .exe, utilisez la commande suivante :
   pyinstaller --onefile --icon=logo.ico app.py
   (Cela créera un fichier .exe dans le dossier 'dist')

Structure du projet :
- app.py : Le script principal du navigateur
- logo.ico : Icône de l'application
- requirements.txt : Liste des dépendances nécessaires

Utilisation :
- Lors du démarrage, un premier onglet avec la page par défaut s'ouvre.
- Cliquez sur "+" pour ouvrir un nouvel onglet.
- Utilisez les boutons "←", "→", "🔄" pour naviguer, et "Home" pour revenir à la page d'accueil.

Instructions après téléchargement :
Extraction :

Une fois le fichier ZIP téléchargé, commencez par l'extraire dans un dossier de votre choix.
Assurez-vous que tous les fichiers (par exemple, app.py, logo.ico, et requirements.txt) se trouvent dans le même répertoire.
Création de l'exécutable (.exe) :

Ouvrez l’invite de commandes sur votre système (Windows).
Naviguez jusqu’au répertoire où vous avez extrait les fichiers. Vous pouvez le faire avec la commande suivante :
bash
Copier le code
cd "chemin/vers/le/dossier"
Une fois dans le bon répertoire, utilisez PyInstaller pour créer l'exécutable. Saisissez cette commande :
bash
Copier le code
pyinstaller --onefile --icon=logo.ico app.py
Cette commande effectuera les opérations suivantes :
Elle empaquetera tous les fichiers nécessaires pour exécuter le navigateur dans un seul fichier exécutable (.exe).
Elle ajoutera l’icône personnalisée logo.ico au fichier exécutable.
Fichier .exe généré :

Une fois la commande exécutée avec succès, vous trouverez votre fichier .exe dans le dossier dist généré automatiquement.
Déplacez le fichier .exe à l’endroit où vous souhaitez conserver votre navigateur ou partagez-le avec d’autres.
Remarque :
Première exécution : Lors de la première exécution, le fichier .exe peut prendre un peu de temps pour démarrer, car il doit configurer les fichiers nécessaires en arrière-plan.
Si vous rencontrez un problème pendant le processus, assurez-vous que toutes les dépendances sont correctement installées en exécutant :
bash
Copier le code
pip install -r requirements.txt
Contribution :
Vous souhaitez participer au développement de Lynx Browser ? Contactez-nous ou ouvrez une Pull Request sur notre dépôt GitHub.
Proposez vos idées, améliorez le code ou ajoutez de nouvelles fonctionnalités.
Merci de contribuer à l'amélioration de Lynx Browser et de promouvoir l'open source ! 😊
