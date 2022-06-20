▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒
░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
▀▄▀▄  			    Endless                 ▄▀▄▀
░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░
▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓


Disclaimer: 
+If game is rendered unstartable, you are the only one responsible. Therefore using this tool, you agree to the "risks".
++You can always use the Original NCSoft Launcher to restore files to Original and start the game <3


Credits:
+ Miyako - Inspired by BnS-Ark Tool!
+ Endless aka Kogaru - Recoded from scratch and improved!
+ ronny1982 - For bnsdat tool
+ LokiReborn - For porting bnsdat to C# ,adding AuthToken, VersionCheck and BXML4
+ Yevvie - For Icons, Splash art and BnS Buddy Forum images
+ Airix - For providing a Battleground Fix
+ GunerX - For providing upk numbers for animation toggles & community
+ Yeti - For finding AMD ULPS interfering with bns performance
+ Megai2 - For his dx12 proxy mod for better bns performance
+ Fukki - For MUI Cache method to get client path of Garena regions
+ Pilao and Community - For PluginLoader and more
+ Pilao - New and improved dat handling
+ LEaN and Vectoriel - For Signature Bypass
+ Tonic and Hora - For Animations and Effects toggles


Requirements:
+ .Net Framework 4.7.2 (not client profile)
++ A brain :P


FUTURE FEATURES:
+ Remotely fetch mods/addons/splash from server
+ Game Updater (na/eu/kr/jp/tw)
+ Game Installation Cleaner
+ Reworked: QoL Toggles to work by position of bytes
+ ReAdded: Game Translation for License users


Change Log:
Update 6.0.1.5
+ Added: Client INI Editor
+ Added: Destination folder button in bnspatch addon manager for those having 2 different documents folder
+ Removed: Annoying popup when uninstalling mods that was used for debugging teehee

Update 6.0.1.4
+ Fixed Bug: Wrong registry path was used for Russian client
+ Fixed Bug: FastColoredTextBox would not render colors when scrolling
+ Fixed Bug: Tray icon would have a weird behaviour
+ Fixed Bug: Weird behaviour when selecting an xml file from the dat editor

Update 6.0.1.3
+ Fixed Bug: Wrong registry path was used for Chinese client
+ Fixed Bug: Refreshing mods will not let you know which mod is already installed
+ Fixed Bug: Uninstalling a secondary sub mod deletes the original mod folder

Update 6.0.1.2
+ Added: Home page with inbox

Update 6.0.1.1
+ Fixed Bug: Toggles for animations and effects were inverted

Update 6.0.1.0
+ Added: Class toggles in extras are now working

Update 6.0.0.9
+ Fixed Bug: Changing language would not reset Splash path

Update 6.0.0.8
+ Fixed Bug: Registry conflicted with TW and KR because they both use the same registry path

Updater 3.0.0.2
+ Fixed Bug: Missing Dependencies

Update 6.0.0.7
+ Added: File version on unhandled error prompts
+ Fixed Bug: Opening/Saving xml files from extracted bin folder would not find the path
+ Fixed Bug: Extracting the bin file would not populate treeview
+ Fixed Bug: Path for the tools to unpak and repak would not work if a space was found in pc user name

Update 6.0.0.6
+ Added: BnS Buddy rename detection to prevent crypto errors
+ Fixed Bug: Toggling faster load and startup would cause error if one file was missing
+ Fixed Bug: Included updater in BnS Buddy was not packed in a zip resulting in an error
+ Fixed Bug: Game Install detections would still proceed even if the game path did not exist

Update 6.0.0.5
+ Fixed Bug: Update button would still be grayed out when new update is available

Update 6.0.0.4
+ Reworked: Installing mods now uses directory symlinks instead of file symlinks due to overlap file name issue

Update 6.0.0.3
+ Fixed Bug: Closing the add new profile window with text in textbox would freeze app
+ Fixed Bug: New check for deprecated profile was not properly implemented

Update 6.0.0.2
+ Fixed Bug: Having old deprecated profiles would cause issues when generating user list

Update 6.0.0.1
+ Added: Clicking on the tray icon will restore BnS Buddy UI
+ Fixed Bug: New Instance window would be too small and wont match text size
+ Fixed Bug: Duplicate registry profiles would cause errors
+ Fixed Bug: Added a direcory exist check for install paths just in case it no longer exists based from registry

Updater 3.0.0.1
+ Fixed Bug: When updater could not connect to internet it would set online version as debug text

Update 6.0.0.0
+ Updated: UI to MaterialSkin for a fresh new modern look
+ Refactored: Entire code & Cleaned up dependencies