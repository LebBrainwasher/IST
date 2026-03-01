Surveillance Tactique Mobile
Une application web légère, réactive et sécurisée conçue pour la saisie rapide d'observations lors de missions de surveillance tactique. Optimisée pour une utilisation mobile sur le terrain.
🚀 Caractéristiques
Interface Tactique : Mode sombre natif pour la discrétion et la préservation de la vision nocturne.
Saisie Rapide : Boutons d'actions prédéfinis (START, STOP, OBS, CONT, DIR) pour une réactivité maximale.
Gestion Intelligente des Plaques : Formatage automatique des immatriculations (SIV et anciens formats) avec mise en évidence visuelle.
Dictionnaire Phonétique : Conversion automatique de l'alphabet aéronautique (Alpha, Bravo, Charlie...) en lettres lors de l'export.
Export/Import JSON : Sauvegarde locale des sessions incluant la date du jour et l'heure précise.
Rapport PDF : Génération de rapports propres via la fonction d'impression, optimisée pour le papier.
Zéro Dépendance : Fonctionne entièrement côté client (HTML/JS pur), aucune base de données ou serveur requis.
📸 Aperçu
L'interface se divise en trois zones :
Header : Titre et horloge temps réel synchronisée.
Zone de Saisie : Sélecteur de type d'événement et champ de texte intelligent.
Journal de Bord : Tableau dynamique des événements avec possibilité de modification ou suppression.
🛠️ Installation
Clonez le dépôt :
git clone [https://github.com/votre-utilisateur/surveillance-tactique-mobile.git](https://github.com/votre-utilisateur/surveillance-tactique-mobile.git)


Ouvrez simplement le fichier Surveillance_Tactique_Mobile.html dans n'importe quel navigateur moderne (Chrome, Safari, Firefox).
Pour une utilisation mobile optimale, ajoutez le fichier à votre écran d'accueil via les options de votre navigateur mobile (PWA).
📖 Utilisation
Saisie d'une plaque : Tapez IMMATRICULATION : suivi de la plaque en langage clair ou phonétique (ex: IMMATRICULATION : ALPHA BRAVO 123 CD). L'application convertira et formatera automatiquement.
Modification : Cliquez sur la description d'une ligne dans le tableau pour ouvrir la fenêtre de modification ou de suppression.
Export : Utilisez le bouton Export pour télécharger votre session au format .json avec la date du jour intégrée.
Import : Rechargez une session précédente pour la consulter ou la compléter.
🧪 Technologies
HTML5 / CSS3 (Variables CSS, Flexbox)
JavaScript Vanille (ES6+)
Format de données : JSON
📄 Licence
Ce projet est sous licence MIT.
Note : Cette application a été développée pour répondre à des besoins opérationnels de terrain privilégiant la rapidité et la fiabilité.
