# WebDiagnostic PC - Assistant de Diagnostic de Périphériques

Un outil web interactif et moderne permettant de tester et diagnostiquer la communication, l'état physique et la réactivité de vos périphériques de saisie et de communication.

## 🚀 Fonctionnalités

- **Assistant de Scan Interactif (2 modes) :**
  - *Scan Rapide :* Test de réactivité de la souris, des 3 clics principaux (gauche, droit, molette) et de 3 touches aléatoires.
  - *Scan Exhaustif (Approfondi) :* Test cinématique, défilement haut/bas de la molette, 3 clics physiques, et vérification unitaire complète de la matrice du clavier.
- **Clavier Interactif Complet (Modèle HP) :** Représentation physique 100 % d'un clavier standard HP (zone alphanumérique, bloc de navigation, pavé numérique) avec détection et mémorisation des touches fonctionnelles et indicateurs de verrouillage LED (NumLock, CapsLock, ScrollLock).
- **Test de Souris indépendant :** Compteurs de clics unitaires (Gauche, Milieu, Droit) et détection de la molette pour repérer les anomalies matérielles (comme le double-clic involontaire).
- **Diagnostics Multimédia :** Modules de tests pour la webcam, le microphone (avec vu-mètre), les haut-parleurs (stéréo gauche/droite), les manettes de jeu (Gamepad API) et l'écran (recherche de pixels morts).
- **Rapport de Diagnostic :** Génération et exportation d'un rapport technique complet au format `.txt`.

## 🛠️ Technologies utilisées

- **HTML5 & Vanilla JavaScript** (pour la capture précise des événements matériels)
- **Tailwind CSS** via CDN (pour l'interface graphique moderne et adaptative)
- **Lucide Icons** (bibliothèque d'icônes)

## 💻 Comment l'utiliser localement ?

1. Clonez ce dépôt ou téléchargez le fichier `index.html`.
2. Ouvrez simplement le fichier `index.html` dans votre navigateur préféré. Aucune installation ni serveur local n'est requis.
