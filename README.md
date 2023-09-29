# How to create your own branch + Test App
## PLEASE LET YOUR SUB-TEAM LEAD CREATE NEW BRACHES, AS THE BRANCHING PROCEDURE IS PRETTY VOLATILE AND REQUIRES KNOWLEDGE OF GIT CLI
1. Create a new branch
2. Create a new *blank* PowerApp
3. Download a copy of the new PowerApp
4. Extract the copy of the PowerApp with `pac canvas unpack --sources <Some dir to put all the sources in> --msapp <Path to downloaded file>`
5. Copy lines 100-121 of `CanvasManifest.json` to the new branch (Mainly `FileID` and `Id`, I think, possibly more testing required to narrow down)
6. Copy the `AppName` on line 123 to the new branch
7. Commit your changes
8. Upload to GitHub
9. Link the new PowerApp to the new Branch
10. If all went well, you now have a new powerapp linked to a new branch

> If any of the above steps fail, your app will most likely be blast into oblivion (I have lost about 5 apps trying to get this procedure down)