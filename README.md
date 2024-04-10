# HoudiniEngineForUnreal-ContentExamples
Content Examples for the Houdini Engine for Unreal plug-in.

Unreal Version 5.2
Houdini Version 20.0.594

Version 1.0

--------------------------------------------

GETTING STARTED

This project contains many examples of Houdini & Houdini Engine-related workflows and tools.

The Content examples are available as a content plugin that can be easily added to an existing project of your choice.
This repository also offers a separate project that you can use if you want to browse the content example by themselves.

You can find Topics broken down into specific maps, that can be found in the `ContentExamples/Maps` folder of the HoudiniEngineExamples plugin. 

To add the content examples to an existing Unreal project, please do the following:
- download and copy the Plugins/Runtime/HoudiniEngineExamples folder into your project.
- make sure that your project already has the main HoudiniEngine plugin installed.
- after opening your project, ensure that both the HoudiniEngine and HoudiniEngineExamples plugins are enabled.
- in your content browser, click on the settings button and check that 'Show Plugin Content' is enabled.
- You can then start browsing the content example by looking in the `ContentExamples/Maps` folder of the Houdini Engine Examples plugin

Alternatively, you can download the entire repository, and use the provided project.
You will need to copy the HoudiniEngine plugin to the 'Plugin/Runtime/HoudiniEngine' folder of the project, as a copy of the main plugin is not included with the ContentExamples.

--------------------------------------------

When opening an example map for the first time, some HDAs will need to be built. To do this, follow the steps below.

Step 1:
Have a version of Houdini Engine plugin installed in your project under
"(Your Project Path)/Plugins/Runtime/HoudiniEngine/"

Step 2:
Open the map of the topic you wish to explore.

Step 3:
In the top menu panel, under `Houdini Engine`, select `Create Session`

Step 4:
With a live session running, under the `Houdini Engine` panel, select `ReCook All`
(Depending on PC performance, it may be better to build HDAs in sections, or one at a timme as you need)

Step 5:
Explore the Levels! Here is a rough guide on best way to explore.
 - Explore left to right for a progressive learning experience, but it is not required.
 - HDAs on the platform are live demos, and worth editing(see the front panel steps for more info)
 - Reading the backboard notes for extra info.
 - Open the HDAs in Houdini to explore the node network and seeing more comments.

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

Instacers
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
 - Creating, Editing and using Edit Layers
 - Basics of Heightfield Editing in Houdini
 - Actor Spawning
 - Texture Generation for Terrain
 - Landscape Splines

Materials
 - Assinging Existing UE5 Materials
 - Creating Instances of Existing Materials
 - Editing Material Instance Properties
 - Creating Custom Materials
 - Texture Generation

Geometry Collection (GC)
 - Chaos Geometry Collection Setup
 - Facturing Basics
 - Splitting and Emebedding Meshes in GC Assets
 - Using RBD (Rigid Body Dynamics) from Houdini for GC
 - Spawning GC Actors, ie. Anchors, Fields

For more information, please visit https://www.sidefx.com/docs/houdini/unreal/index.html

--------------------------------------------





