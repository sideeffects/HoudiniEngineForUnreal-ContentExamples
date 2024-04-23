# HoudiniEngineForUnreal-ContentExamples

This repository contains the Content Examples for the Houdini Engine for Unreal plug-in.
The whole repository contains a sample project for the content examples, but they can also be downloaded as a Content Plugin via the release page.

Version 1.0

Minimum Unreal Version 5.2

Minimum Houdini Version 20.0.594

Documentation: https://www.sidefx.com/docs/houdini/unreal/index.html

The project/plugin in this repository requires the "HoudiniEngine" plugin to be installed and enabled in Unreal.
You can find the HoudiniEngine plugin in your Houdini installation folder - or can download it in the following Git repository:

https://github.com/sideeffects/HoudiniEngineForUnreal

--------------------------------------------

GETTING STARTED

This project contains many examples of Houdini & Houdini Engine-related workflows and tools.

The Content examples are available as a content plugin that can be easily added to an existing project of your choice.
This repository also offers a separate project that you can use if you want to browse the content example by themselves.

You can find Topics broken down into specific maps, that can be found in the `ContentExamples/Maps` folder of the HoudiniEngineExamples plugin. 

To add the content examples to an existing Unreal project, please do the following:
- Head over to the release page of this repository and download the latest release of the Content Example plugin.
- Extract and copy the HoudiniEngineExamples folder to your project's "Plugins/Runtime/" folder.
- Make sure that your project already has the main HoudiniEngine plugin installed.
- After opening your project, ensure that both the HoudiniEngine and HoudiniEngineExamples plugins are enabled.
- In the HoudiniEngine menu, you should now be able to click on the "Browse Content Examples" menu entry.
- This will open the content examples maps folder in your content browser.

Alternatively, you can also manually access the content examples' maps by:
- Click on the settings button of your content browser, and ensure that 'Show Plugin Content' is enabled.
- You can then start browsing the content examples by looking in the `ContentExamples/Maps` folder of the Houdini Engine Examples plugin.

The final step is to simply explore the Levels! Here is a rough guide on the best way to explore them:
 - Explore left to right for a progressive learning experience, but it is not required.
 - HDAs on the platform are live demos, and worth editing (see the front panel steps for more info)
 - Read the backboard notes for extra info.
 - Open the provided HDAs in Houdini to explore the node network and see more comments.

If you prefer to use the content examples in their separate project, you can download this entire repository, unzip it, and use the provided unreal project.
You will need to copy the HoudiniEngine plugin to the project's 'Plugins/Runtime/HoudiniEngine' folder, as a copy of the main Houdini Engine plugin is not included with the ContentExamples.

--------------------------------------------

When opening an example map for the first time, some HDAs might need to be built. To do this, follow the steps below.

Step 1:
Make sure you have a version of the Houdini Engine plugin installed in your project under
"(Your Project Path)/Plugins/Runtime/HoudiniEngine/"

Step 2:
Open the map of the topic you wish to explore.

Step 3:
In the top menu panel, under `Houdini Engine`, select `Create Session`

Step 4:
With a live session running, under the `Houdini Engine` panel, select `ReCook All`
(Depending on PC performance, it may be better to build HDAs in sections, or one at a time as you need)

Step 5:
Explore the Levels!

--------------------------------------------

Content covered in this project.

Geometry
 - Inputs/Outputs
 - Mesh Editing
 - UV Creation/Editing
 - Normals
 - LODs
 - Collision

Curves
 - Curve Setups
 - Curves Properties
 - Curve Editing
 - Curve Creation from Data
 - Mesh Editing with Curves
 - Mesh Creation with Curves
 - Actor Spawning with Curves + Attributes

Instancers
 - Basics of Actor Types
 - Instancing Actors
 - Splitting Instances
 - Foliage Actor Types
 - Instancing Unreal Classes
 - Editing U-Properties

Landscapes
 - Landscape Inputs
 - Landscape from Houdini Heightfields
 - Creating and Editing Unreal Layers
 - Creating, Editing, and using Edit Layers
 - Basics of Heightfield Editing in Houdini
 - Actor Spawning
 - Texture Generation for Terrain
 - Landscape Splines

Materials
 - Assigning Existing UE5 Materials
 - Creating Instances of Existing Materials
 - Editing Material Instance Properties
 - Creating Custom Materials
 - Texture Generation

Geometry Collection (GC)
 - Chaos Geometry Collection Setup
 - Fracturing Basics
 - Splitting and Embedding Meshes in GC Assets
 - Using RBD (Rigid Body Dynamics) from Houdini for GC
 - Spawning GC Actors, ie. Anchors, Fields

For more information, please visit https://www.sidefx.com/docs/houdini/unreal/index.html

--------------------------------------------





