# Installation

Le tutoriel utilise python (>=3.7) et des Jupyter notebooks (.ipynb) qui permettent de mélanger du code et du texte et d'avoir un environnement agréable pour expérimenter.

Il est possible de réaliser les bots en utilisant d'autres langages de programmations, mais aucune instruction particulière ne sera donnée.

Les étapes d'installation sont les suivantes:
1. Installer python et un package manager ou installer anaconda
2. Installer jupyter notebook et les dépendances nécessaires pour le tutoriel

## Installer python/anaconda
Il y a deux possibilités pour installer un environnement python : soit de n'installer que python, soit d'installer Anaconda. La première solution est plus "légère" et n'installera que ce qui est nécessaire pour le cours, toutefois elle peut être plus compliquée et ne vient pas avec une solution d'interface graphique (il faudra donc lancer certaines commandes depuis le terminal). La deuxième est beaucoup plus "lourde" car il s'agit d'installer tout un environnement d'outils scientifiques python, mais elle a l'avantage d'avoir une interface graphique pour la plupart des cas d'utilisation (il faudra tout de même utiliser le terminal au moment de l'installation, mais plus après).

Il ne faut bien sûr choisir qu'une des deux solutions, pour ceux qui n'ont pas déjà Anaconda et qui ne pensent pas refaire du python en dehors de ce cours, je conseille la première.

1. Installer Python
    - Se rendre sur le [site officiel de python](https://www.python.org/downloads/) et télécharger la dernière version de python pour votre OS.
    - Lors de l'installation, tout peut-être laissé par défaut, mais il faut absolument cocher "Add Python 3.8 to PATH", sinon python ne sera pas disponible depuis la ligne de commande.
    - Vérifier que tout fonctionne en laissant un terminal et en vérifiant que les commandes `python --version` et `pip --version` retourne bien quelque chose. Si non, vous avez dû faire une erreur quelque part.
2. Installer Anaconda
    - Se rendre sur le [site officiel d'Anaconda](https://www.anaconda.com/distribution/) et télécharger la version pour votre OS.
    - Installer Anaconda en laissant tout par défaut.
    - Lancer le programme "Conda navigator" et vérifier que tout fonctionne.
    
## Installer jupyter notebook et les autres dépendances
- Si vous avez installé python: Ouvrez un terminal et exécutez la commande suivante: `pip install jupyter pywikiapi tqdm`. Une fois jupyter installé, vous pouvez lancer le notebook depuis le terminal en tapant `jupyter notebook` ; l'interface du notebook est maintenant accessible dans un navgiateur web à l'adresse (par défaut) `localhost:8888`.
- Si vous avez installé Anaconda: jupyter notebook est déjà installé par défaut, il vous faut juste ouvrir un terminal anaconda depuis un de vos environnement:

![open terminal](https://i.stack.imgur.com/EiiFc.png "Ouvrir un termnial")

et également exécuter `pip install pywikiapi tqdm`.
