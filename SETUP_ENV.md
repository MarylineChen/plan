# Setup de l'environement de dev 

- Rejoindre le projet github avec le lien d'invitation reçu par mail ou la notification Github
- Installer [github desktop](https://desktop.github.com) et se connecter à son compte
- Installer Eclipse
- Installer SonarLint dans Eclipse
  - Suivez [ce lien](https://marketplace.eclipse.org/content/sonarlint#group-details)
  - Glissez déposez le bouton "Install" depuis votre navigateur dans votre logiciel Eclipse
  - Suivez les instructions à l'écran.
- Installer le formatteur de code du groupe dans Eclipse
  - Télécharger le fichier [BUSY_CHESS_FORMATTER.xml](https://github.com/busychess/plan/blob/master/BUSY_CHESS_FORMATTER.xml)
  - Dans Eclipse aller dans les préférences (Alt+W puis P sur Windows, Command + , sur mac)
  - Naviguer vers Java > Code Style > Formatter
  - Cliquer sur "Import" et sélectionner le fichier téléchargé
  - Apply
- Toujours dans les paramètres...
  - Naviguer vers Java > Editor > Save Actions
  - Cocher "Format source code" puis "Format all lines"
  - Cocher "Organize imports"
  - Cocher "Additional actions"
- Cloner le repo git
  - Ouvrir GitHub Desktop
  - Choisir dans le menu de gauche "Add" puis "Clone repository"
  - Choisir celui nommé "busychess/busychess"
  - Selectionner le dossier de destination comme étant votre "eclipse-workspace"
- Dans Eclipse, File > Import > Existing Maven Project
  - Choisir le dossier du dépôt git du projet
  - Il vous propose le pom.xml du projet
  - Finish
 
 Voila !
