J'ai développé un petit outil open source qui se connecte à votre instance Tautulli et génère un catalogue PDF de votre bibliothèque Plex avec :

✨ Ce que ça fait
- 📄 PDF avec poster + titre + synopsis + réalisateur + acteurs + note pour chaque titre
- 🎨 Design dark mode avec page de couverture automatique
- 📚 Compatible Films, Séries, Musique
- 🖥️ Interface graphique native (plus besoin de toucher au code)
- ⚙️ Config sauvegardée (URL Tautulli + clé API) dans un fichier JSON

📦 Installation
pip install requests reportlab pillow customtkinter
python tautulli_catalogue_gui.py

La fenêtre de config s'ouvre automatiquement au premier lancement.
Un bouton "Paramètres" permet de changer l'URL/clé à tout moment.

📥 Téléchargement (exe Windows — aucune installation requise)
➡️ https://github.com/seb67france/Tautulli-Catalogue/releases/download/Tautulli/TautulliCatalogue.exe

⚠️ Prérequis
- Tautulli installé et accessible en réseau
- Python 3.x (version script uniquement)

Testé avec 696 films. Fonctionne aussi pour les séries.
N'hésitez pas à remonter vos bugs ou suggestions ! 🙏
