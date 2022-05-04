# NFPUnrealThirdPersonTemplate
This provides an Unreal Engine template that can get you started using your NFP in a 3rd Person style game quickly.  Not only does this template mimic the existing 3rd Person template, but it also retargets your NFP behind the scenes so that the 3rd person animations work without additional input needed.

## Instructions
1. Follow this video to install your NFP into Daz Studio: https://www.youtube.com/watch?v=FxQSvuRn-_A
2. Install the latest Unreal Engine bridge, using the steps listed here: https://davidvodhanel.com/daz-to-unreal-manually-updating/
* Note - Use this location for the bridge: https://github.com/David-Vodhanel/DazToRuntime/releases.  The one in the Daz Studio github still needs to be updated to this.
3. Download the latest NFP Unreal Third Person Template from here: [Needs url to released package page]
4. In the zip file properties, choose "Unblock"
5. Determine where you have Unreal Engine installed (Probably under C:\Program Files\UE_[version])
6. Unzip the zip file to the Templates subfolder
7. Launch the Unreal Editor
8. In the startup window, under "New Project Categories" select "Games" and click "Next".
![New project](/docimages/SelectTemplate1.png?raw=true "Select new game")
9. Select the "G8 Third Person" template and click "Next."
![Select template](/docimages/SelectTemplate2.png?raw=true "Select the template")
10. Name the project and click "Create Project"</br>
![Name project](/docimages/SelectTemplate3.png?raw=true "Select name")
11. The project will load, and you will be able to hit Play and run around.
![Startup view](/docimages/ProjectStartView.png?raw=true "Project Start View")
12. In Daz Studio, create a new scene and add your NFP.  In Content Library, search for "NFP"and double click on the one you want to use
13. Click on the NFP in the scene heirarchy window (will be under a node titled null), and select "Unparent"
![Unparent](/docimages/Unparent.png?raw=true "Unparent NFP")
14. Select the NFP and then use "File->Send To->Daz to Unreal"
15. Use the default settings and press Accept
16. Go back to the Unreal Editor
17. Look in the World Outliner on the right side, scroll down to the bottom to select the "ThirdPersonCharacter"
18. In the Details panel on the bottom right, look under Mesh, there is a field called "Skelatal Mesh"
19. Set the Skeletal Mesh to your NFP (which should be labeled something like nfp01[nfp#])
20. Hit play and run around
