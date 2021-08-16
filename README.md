# PropertryDebugEditor doc
## Tutorials video
* https://vimeo.com/587533534
## How to start
* Create default Unreal project(423,424,425,426,5.0) anly one
* Put the PropertyDebug folder into your project Plugins path(YourProjectName/Plugins/)
* Open the project and load the plug-in module
* Enter the PropertryDebugEditor mod 

## Function
* Add buttion： Add a tag for search
* Clean buttion： Clean up all tags in the current tab page
* Drop down： Drop down the storage list, you can change the current configuration name, and press Enter to rename
* IncludeSuper：Whether to filter inherited variables or functions
* Padding： The spacing of the data displayed in the window
* ParmName* ：Enter the cm command here, press up and down to select, press Enter to confirm, and use "." to enter a deeper level
## Data Viewport
* Can be displayed in the editor or at runtime
* Need extra work under runtime
* Create a blueprint class, inherit from AADebugPropertyActor
* Drag the AADebugPropertyActor blueprint into the scene
* Click the player button，You can view the data changes at runtime

