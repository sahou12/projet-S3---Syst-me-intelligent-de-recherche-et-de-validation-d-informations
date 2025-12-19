# projet_S3-Systeme-intelligent-de-recherche-et-de-validation-d-informations
Nous avons choisi de développer une application d’assistance à la vérification d’informations, capable de rechercher des sources sur internet et d’analyser leur fiabilité à l’aide de l’intelligence artificielle.

Elle combine :
-une recherche web via l’API Tavily
-une analyse IA via l’API Mistral
-un affichage structuré des résultats
-l’export des réponses en TXT ou PDF

L’objectif est d’aider l’utilisateur à déterminer si une information est vraie, fausse ou non prouvée, à partir de sources fiables.

Dans le fichier Python, renseignez vos clés API :
TAVILY_KEY = "VOTRE_CLE_API_TAVILY"
MISTRAL_KEY = "VOTRE_CLE_API_MISTRAL"

Avant d’exécuter le projet, assurez-vous d’avoir :
Python 3.9 ou plus

Installer les bibliothèques Python suivantes :
-tkinter
-requests
-pillow
-reportlab
-tavily

Pour installer les bibliothèques, executez dans le terminal :
pip install requests pillow reportlab tavily-python

(Tkinter est généralement déjà installé avec Python)

Pour lancer l'application, executez dans le terminal:
python main.py
