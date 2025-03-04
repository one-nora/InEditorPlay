# This was tested on patch 16c, make sure you are on that version for this to work
# Installation
1. Download the package and import the unity package
	1. To download, click on the unity package "InEditorPlay"
	2. Then look for the download icon on the left, it should say "Download raw file"
	3. Click it to download the package
	4. If any errors show up after importing, restart the project
2. Add a FirstRoom from the "ULTRAKILL Assets" folder and NOT the "RudeEditorPrefabs" folder, otherwise the player wont spawn
3. Copy your "Saves" and "Preferences" folder from your ultrakill install into the root folder of the project (NOT inside Assets)
4. Go to RUDE->Play mode->Edit config
	1. Click on "Set ULTRAKILL root path"
	2. A window will popup, navigate to your ULTRAKILL install and select the "ULTRAKILL" folder
5. Click play and wait, it will take long to load

# Disclaimers
* Unity may get stuck in big scenes during play mode

# Tips
* Set the FirstRoom tag to EditorOnly so it doesnt export
* To set the difficulty before playing (or while playing, both work), you can go to Rude->Play mode->Edit config, and click on the difficulty you want
* This works with steam, although steam integration is disabled by default and can be enabled via Rude->Play mode->Set player preferences
* Pressing PgUp will update the shaders in play mode (This can be changed in Assets/Editor/PlayMode/PlayModeConfig)
* Restart mission works (quit mission doesnt, so dont touch that)

# Limitations
* Some settings in the menu may not work
* Custom scripts that use harmony patching dont work

# Known issues
* Blood splatters dont appear on surfaces
* Outlines dont work (they do, press the quick shader key)
* UI Elements look black
* Oil on enemies looks weird (press the quick shader key)