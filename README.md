# j2aConverter
A plugin for jetbrains IDEs that adds an option to the in-editor menu to convert valid json from request payloads or wherever else, into a PHP associative array.

# To Use
clone this code and open it into Intellij IDEA, and use the gradle task `buildPlugin` located under /Tasks/intellij/ in the gradle tool bar located on the right side of the screen.
This builds your plugin and zips it into the <project-name>/build/distributions folder. Go the IDE plugin menu and click the cog, select "Install Plugin from Disk" and select your
zip file.
When you select a valid json object and bring up the editor menu, at the top should be an option to convert the JSON into an assocaiative array.
