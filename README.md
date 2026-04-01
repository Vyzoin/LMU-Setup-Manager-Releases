# LMU Setup Manager

Petit logiciel Python avec interface pour importer rapidement des setups Le Mans Ultimate 
ainsi que convertir en bon format les fichiers de livrées

## Installation

Exécuter LMUSetupManager_Setup.exe
Ouvrir LMUSetupManager via le menu démarrer
Si une maj a besoin de se faire, elle se fera après avoir demandé votre accord, si une erreur s'affiche à la fin du téléchargement, 
c'est normal pour le moment. Relancer le logiciel et la maj aura normalement été effectué.

## Utilisation
IMPORTATION DES SETUPS
1. Clique sur **Choisir setup / ZIP...** et selectionne un fichier setup ou une archive **.zip** (bundle).
2. Le circuit est detecte surtout via le **nom du fichier** ou du **ZIP** ; pour un ZIP, les **dossiers internes** peuvent aussi servir de secours.
3. Clique sur **Importer** : un seul fichier est **deplacé** ; un ZIP extrait tous les setups (.svm, .json, .ini, .txt) dans le dossier du circuit puis **deplace** l'archive dans ce meme dossier.

IMPORTATION DES FICHIERS DE LIVREES
1. Clique sur **dossier source**, qui est le dossier avec vos fichiers .png.
2. Clique sur **dossier destination**, qui est le dossier ou les .tga vont se déposer dans les settings LMU.
3. Clique maintenant sur importer et les fichiers sont convertis et déplacés.

<img width="1808" height="963" alt="image" src="https://github.com/user-attachments/assets/a20bde5b-df88-4037-8dc1-108e4f3ef803" />
<img width="1810" height="972" alt="image" src="https://github.com/user-attachments/assets/34091592-d623-45a8-acaa-3cdd70016fe6" />


Small Python program with an interface for quickly importing Le Mans Ultimate setups and converting livery files to the correct format.

## Installation
Run LMUSetupManager_Setup.exe. Open LMUSetupManager from the Start menu. If an update is required, it will be performed after requesting your approval. If an error message appears at the end of the download, this is normal. Restart the program, and the update should be complete.

## Usage
IMPORTING SETUPS

1. Click on Choose setup / ZIP... and select a setup file or a .zip archive (bundle).
2. The track is detected primarily by the file or ZIP name; for a ZIP, the internal folders can also be used as backups.
3. Click on Import: only one file is moved; a ZIP extracts all the setups (.svm, .json, .ini, .txt) into the track folder and then moves the archive into the same folder.
  
IMPORTING LIVERY FILES

1. Click on the source folder, which is the folder containing your .png files.
2. Click on the destination folder, which is the folder where the .tga files will be placed in the LMU settings.
3. Now click on import, and the files will be converted and moved.
