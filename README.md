Brief-Streamlit
Application Streamlit — Espace utilisateur

Ce projet a été réalisé dans le cadre de ma formation Data Analyst afin de mettre en pratique l'utilisation de Streamlit. Il n'a pas pour but de devenir une vraie application fonctionnelle. Les données (comme accounts.csv) sont toutes fictives.

Fonctionnement
L'accès à l'application nécessite une authentification. Vous retrouverez les comptes dans accounts.csv (par exemple utilisateur / mdp123 ou admin / admin123). Vous pouvez, si vous le souhaitez, ajouter d'autres comptes.
La session est maintenue grâce à st.session_state.
Le menu latéral permet de naviguer entre l'accueil et la galerie photos (mes photos affichées sur 3 colonnes).
Vous pouvez vous déconnecter à tout moment avec le bouton « Se déconnecter ».
Le fichier app_dataviz.py est un second dashboard : le trafic aérien (données Seaborn) avec filtres et graphiques interactifs.
Installation et lancement en local
Créez un dossier, par exemple C:/Projet1, et ouvrez-le dans VS Code.
Dans le terminal, placez-vous dans ce dossier : cd C:/Projet1
Clonez le dépôt et entrez dedans : git clone https://github.com/mmesaraal-up/Projet-animaux.git puis cd Projet-animaux
Créez l'environnement virtuel : python -m venv venv
Activez-le : .\venv\Scripts\activate (Mac/Linux : source venv/bin/activate). Le préfixe (venv) doit apparaître dans le terminal.
Installez les dépendances : pip install -r requirements.txt
Lancez l'application : streamlit run app_securisee.py (ou streamlit run app_dataviz.py pour le dashboard)

Python 3.10 à 3.12 conseillé. Ctrl + C dans le terminal pour arrêter l'application.

Démo en ligne : https://projet-animaux-efncte7pbtrzzzfc6hxp4u.streamlit.app/
