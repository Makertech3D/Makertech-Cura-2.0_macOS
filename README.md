# Makertech-Cura-2.0_macOS

Makertech Cura V2.0

Resource files for Makertech 3D printers for installing the Makertech Edition of Cura on macOS.

Built and tested on version 4.6.1 of Ultimaker Cura.

Install instructions:
1. Download and install Ultimaker Cura v4.6.1 from [here](https://github.com/Ultimaker/Cura/releases/tag/4.6.1).
2. Right click on application and click "show package content".
3. Go to Content/resources/plugins/plugins
4. Delete folders: "VersionUpgrade" and " UpdateChecker".
5. Go back to Content/resources
6. Delete the resources folder and the "icon.icns" file.
7. Copy in the resources folder and icons.icns files you have downloaded from this repository.
8. Close package content.
9. Right click on Cura application and click open.
10. A message will appear, ignore and click open again.
11. Done.

If you receive an error message that the package is damaged:

Dismiss that error.

Open a terminal window and execute:

sudo xattr -rds com.apple.quarantine /Applications/Ultimaker\ Cura.app

You can now open Cura.
