# Installation
1. Install the burst package
	1. Go to Window->Package manager
	2. Search for "burst" (make sure you are on "Unity registry") and install the 1.6.6 version
	3. Restart the project
2. Download and import the unity package
	1. To download, click on the unity package "InEditorPlay"
	2. Then look for the download icon on the left, it should say "Download raw file"
	3. Click it to download the package
	4. If any errors show up after importing, restart the project
3. Add a FirstRoom from the "ULTRAKILL Prefabs\Wrapped Prefabs" folder and NOT the "RudeEditorPrefabs" folder, otherwise the player wont spawn
4. Copy your "Saves" and "Preferences" folder from your ultrakill install into the root folder of the project (NOT inside Assets)
5. Click play and wait, it will take long to load

# Tips
* Set the FirstRoom tag to EditorOnly so it doesnt export
* To set the difficulty before playing (or while playing, both work), you can go to Rude->Play mode->Set player preferences, and click on the difficulty you want
* This works with steam, although steam integration is disabled by default and can be enabled via Rude->Play mode->Set player preferences

# Limitations
* Custom scripts that use harmony patching dont work
* Trams continue even after the player gets off (this is intentional otherwise the tram simulation doesnt work)

# Known issues
* Blood splatters dont appear on surfaces
* Outlines dont work
* UI Elements look black
* Oil on enemies looks weird