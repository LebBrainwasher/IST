# Surveillance Tactique Mobile
Une application web légère, réactive et sécurisée conçue pour la saisie rapide d'observations lors de missions de surveillance tactique. Optimisée pour une utilisation mobile sur le terrain.

# 🚀 Caractéristiques
- <b>Interface Tactique :</b> Mode sombre natif pour la discrétion et la préservation de la vision nocturne.
- <b>Saisie Rapide :</b> Boutons d'actions prédéfinis (START, STOP, OBS, CONT, DIR) pour une réactivité maximale.
- <b>Gestion Intelligente des Plaques :</b> Formatage automatique des immatriculations (SIV et anciens formats) avec mise en évidence visuelle.
- <b>Dictionnaire Phonétique :</b> Conversion automatique de l'alphabet aéronautique (Alpha, Bravo, Charlie...) en lettres lors de l'export.
- <b>Export/Import JSON :</b> Sauvegarde locale des sessions incluant la date du jour et l'heure précise.
- <b>Rapport PDF :</b> Génération de rapports propres via la fonction d'impression, optimisée pour le papier.
- <b>Zéro Dépendance :</b> Fonctionne entièrement côté client (HTML/JS pur), aucune base de données ou serveur requis.

# 📸 Aperçu
L'interface se divise en trois zones :
1. <b>Header :</b> Titre et horloge temps réel synchronisée.
2. <b>Zone de Saisie :</b> Sélecteur de type d'événement et champ de texte intelligent.
3. <b>Journal de Bord :</b> Tableau dynamique des événements avec possibilité de modification ou suppression.
# 🛠️ Installation
1. Clonez le dépôt :
git clone [https://github.com/votre-utilisateur/surveillance-tactique-mobile.git](https://github.com/votre-utilisateur/surveillance-tactique-mobile.git)

2. Ouvrez simplement le fichier Surveillance_Tactique_Mobile.html dans n'importe quel navigateur moderne (Chrome, Safari, Firefox).
3. Pour une utilisation mobile optimale, ajoutez le fichier à votre écran d'accueil via les options de votre navigateur mobile (PWA).
# 📖 Utilisation
- <b>Saisie d'une plaque :</b> Tapez IMMATRICULATION : suivi de la plaque en langage clair ou phonétique (ex: IMMATRICULATION : ALPHA BRAVO 123 CD). L'application convertira et formatera automatiquement.
- <b>Modification :</b> Cliquez sur la description d'une ligne dans le tableau pour ouvrir la fenêtre de modification ou de suppression.
- <b>Export :</b> Utilisez le bouton Export pour télécharger votre session au format .json avec la date du jour intégrée.
- <b>Import :</b> Rechargez une session précédente pour la consulter ou la compléter.
# 🧪 Technologies
- <b>HTML5 / CSS3</b> (Variables CSS, Flexbox)
- <b>JavaScript Vanille</b> (ES6+)
- <b>Format de données :</b> JSON
# 📄 Licence
Ce projet est sous licence MIT.
Note : Cette application a été développée pour répondre à des besoins opérationnels de terrain privilégiant la rapidité et la fiabilité.
