# 🌌 Fortnite: Heure Zéro - Countdown
Un site web immersif et interactif servant de compte à rebours pour l'événement live "Heure Zéro" (Fin du Chapitre 6) de Fortnite.
Ce projet a été conçu pour être utilisé comme page d'accueil pour les fans ou comme overlay OBS pour les streamers en attente de l'événement.
## ✨ Fonctionnalités
 * 🕒 Compte à rebours synchronisé : Calé précisément sur le samedi 29 novembre 2025 à 20h00 (CET).
 * 🌍 Détection de fuseau horaire : Affiche automatiquement l'heure locale du visiteur (pratique pour les communautés internationales).
 * 🎨 Animation "Rift" (Canvas) :
   * Génération de particules dynamiques.
   * Effet de fissures (éclairs) aléatoires rappelant l'instabilité du Point Zéro.
   * Fond dégradé animé fluide.
 * ⚡ Effets Visuels : Titres avec effets "Glitch" et néons CSS.
 * 📱 100% Responsive : S'adapte parfaitement aux mobiles, tablettes et écrans larges.
## 🚀 Démo / Aperçu
Vous pouvez voir le projet en direct ici : https://ninteli.github.io/fortnite-timer-zero-hour/
## 🛠️ Installation et Utilisation
Ce projet est une page statique (HTML/CSS/JS pur). Aucune installation de serveur (Node.js, PHP, etc.) n'est nécessaire.
 * Cloner le dépôt :
   git clone [https://github.com/ninteli/fortnite-zero-hour.git](https://github.com/ninteli/fortnite-zero-hour.git)

 * Lancer :
   * Ouvrez simplement le fichier index.html dans votre navigateur.
⚙️ Personnalisation
Vous pouvez modifier facilement les paramètres dans le fichier index.html :
 * Changer la date cible : Cherchez la variable targetDate dans le script.
   // Format: AAAA-MM-JJTHH:MM:SS+Fuseau
const targetDate = new Date("2025-11-29T20:00:00+01:00").getTime();

 * Modifier le nom du créateur :
   * Cherchez la ligne NINTELI • FAN SITE dans le HTML pour mettre votre propre pseudo.
## 🎥 Pour les Streamers (OBS/Streamlabs)
Ce site est optimisé pour le streaming :
 * Ajoutez une source "Navigateur" dans OBS.
 * Cochez la case "Fichier local" et sélectionnez le index.html.
 * Réglez la largeur sur 1920 et la hauteur sur 1080.
 * Optionnel : Utilisez la clé chromatique (Chroma Key) si vous souhaitez rendre le fond transparent, bien que le fond animé soit conçu pour servir d'écran d'attente complet.
## 🤝 Contribuer
Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une "Issue" si vous trouvez un bug dans l'animation Canvas ou à proposer une "Pull Request".
## ⚠️ Disclaimer / Droits
Ce projet est un site de fan non officiel. Il n'est pas affilié, approuvé ou sponsorisé par Epic Games.
Les éléments graphiques et noms (Fortnite, Zero Point) sont la propriété d'Epic Games.
# Code avec ❤️ par Ninteli