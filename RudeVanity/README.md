# Installation
1. Download the package and import the unity package
	1. To download, click on the unity package "InEditorPlay"
	2. Then look for the download icon on the left, it should say "Download raw file"
	3. Click it to download the package
	4. If any errors show up after importing, restart the project
2. Add a FirstRoom from the "ULTRAKILL Assets" folder and NOT the "RudeEditorPrefabs" folder, otherwise the player wont spawn
3. Copy your "Saves" and "Preferences" folder from your ultrakill install into the root folder of the project (NOT inside Assets)
4. Click play and wait, it will take long to load

# Disclaimer
It is likely that unity will crash after exporting any bundle for the first time, but it will only be ONCE and wont repeat ever. In this case opening up unity again works fine and you wont lose your scene because of this crash since its saved before exporting 

# Tips
* Set the FirstRoom tag to EditorOnly so it doesnt export
* To set the difficulty before playing (or while playing, both work), you can go to Rude->Play mode->Set player preferences, and click on the difficulty you want
* This works with steam, although steam integration is disabled by default and can be enabled via Rude->Play mode->Set player preferences

# Limitations
* Custom scripts that use harmony patching dont work

# Known issues
* Blood splatters dont appear on surfaces
* Outlines dont work
* UI Elements look black
* Oil on enemies looks weird