# 🌌 Fortnite: Heure Zéro - Countdown
Un site web immersif et interactif servant de compte à rebours pour l'événement live "Heure Zéro" (Fin du Chapitre 6) de Fortnite.
Ce projet propose deux versions :
 * Version Immersive : Avec fond animé (particules, failles) pour une utilisation en page d'accueil ou écran d'attente.
 * Version Stream (OBS) : Fond transparent et design épuré pour l'incrustation directe sur vos lives.
## ✨ Fonctionnalités
 * 🕒 Compte à rebours synchronisé : Calé précisément sur le samedi 29 novembre 2025 à 20h00 (CET).
 * 🌍 Détection de fuseau horaire : Affiche automatiquement l'heure locale du visiteur.
 * 🎨 Animation "Rift" (Version Web) : Génération de particules et fissures instables rappelant le Point Zéro.
 * 🎥 Mode Streamer (Version OBS) : Fond transparent, contraste élevé et optimisé pour ne pas consommer de ressources CPU.
 * 📱 100% Responsive : S'adapte à tous les écrans.

## 🚀 Démos en ligne
 * Version Web (Animation complète) : https://ninteli.github.io/fortnite-timer-zero-hour/
 * Version OBS (Overlay transparent) : https://ninteli.github.io/fortnite-timer-zero-hour/obs

## 🛠️ Installation et Utilisation
Ce projet est statique (HTML/CSS/JS pur). Aucune installation complexe n'est requise.
 * Cloner le dépôt :
   git clone [https://github.com/ninteli/fortnite-timer-zero-hour.git](https://github.com/ninteli/fortnite-timer-zero-hour.git)

 * Lancer :
   * index.html : Pour la version complète avec animation.
   * obs.html : Pour la version overlay stream.

## 🎥 Guide pour Streamers (OBS / Streamlabs)
Vous pouvez intégrer le timer directement via l'URL sans télécharger les fichiers :
 * Ajoutez une source "Navigateur" dans OBS.
 * Dans le champ URL, collez :
   https://ninteli.github.io/fortnite-timer-zero-hour/obs
   (Ou sélectionnez le fichier local obs.html si vous avez téléchargé le projet)
 * Réglez les dimensions : Largeur 1920 / Hauteur 600.
 * Fond transparent : Le fond est déjà transparent, pas besoin de filtre Chroma Key !

## ⚙️ Personnalisation
Vous pouvez modifier les paramètres dans les fichiers .html :
 * Changer la date cible : Cherchez la variable targetDate dans le script.
   // Format: AAAA-MM-JJTHH:MM:SS+Fuseau
const targetDate = new Date("2025-11-29T20:00:00+01:00").getTime();

## 🤝 Contribuer
Les contributions sont les bienvenues ! N'hésitez pas à ouvrir une "Issue" ou à proposer une "Pull Request" pour améliorer les animations ou le code.

## ⚠️ Disclaimer / Droits
Ce projet est un site de fan non officiel. Il n'est pas affilié, approuvé ou sponsorisé par Epic Games.
Les éléments graphiques et noms (Fortnite, Zero Point) sont la propriété d'Epic Games.
Code avec ❤️ par Ninteli
