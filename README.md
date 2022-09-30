[![Cesium for Unreal Logo](Images/Cesium-for-Unreal-Logo-WhiteBGH.jpg)](https://cesium.com/unreal-marketplace?utm_source=cesium-unreal&utm_medium=github&utm_campaign=unreal)

# Cesium VR Tutorial Series

The [Cesium for Unreal VR Tutorial Series](https://www.unrealengine.com/marketplace/en-US/product/fc21a5013d8d4821b8c7dc88e94ca0ed) covers strategies and solutions for several common challenges that come with building global-scale applications in VR using [Cesium for Unreal](https://www.unrealengine.com/marketplace/en-US/product/87b0d05800a545d49bf858ef3458c4f7). 

This repository holds example levels and code for all the features described in the tutorial series. This series serves as a guide for recommend practices for VR application design and user ergonomics you can use in your projects. Each tutorial will describe the UX challenge, our design thinking, and the Blueprint code for each feature. New tutorials will be added in frequently so check back soon!

<p align="center">
<img src="Images/Cesium-VR-Headset.jpg" alt="Cesium VR Headset"/>
</p>

### :rocket: Get started with the tutorial

You will need to download the [Cesium for Unreal plugin from the Unreal Engine Marketplace](https://cesium.com/unreal-marketplace?utm_source=cesium-unreal&utm_medium=github&utm_campaign=unreal).

If you are new to the Cesium For Unreal plugin, check out the [Quickstart](https://cesium.com/learn/unreal/unreal-quickstart/) tutorial.

## :video_game: VR Device Compatibility

We tested the inputs used in this project on Meta Quest 2, and are confident the inputs will work with Meta Quest and Rift devices using the Touch controllers. We have added reasonable corresponding inputs for other VR headsets such as the HTC Vive and Valve Index, but have not tested them. If you use any of these headsets, we'd love to get your feedback and build it into the tutorials.

If you are using a VR headset not mentioned above, please add the corresponding bindings for your controller for each input action / axis. For more information on setting up inputs, see the [Unreal Engine docs](https://www.unrealengine.com/en-US/blog/input-action-and-axis-mappings-in-ue4). For an example of setting up inputs across different VR devices, see the [VR Template](https://docs.unrealengine.com/4.27/en-US/Resources/Templates/VRTemplate/) project.

## :world_map: Tutorial Descriptions

The features in this Unreal Engine Project are separated into individual levels with each level corresponding to a single tutorial. Each level builds upon the previous levels. If you would like to see a singular feature in action, open the level within the tutorial's corresponding folder to try it out. Open the level within the "Main" folder if you would like to see all of the features combined into one experience. 

### :one: Tutorial 1 - Teleportation, Line Traces, and Height Correction

In the first tutorial we cover teleporting the player long distances across the world and fetching higher levels of detail on 3D Tiles from a distance. This tutorial also covers common issues in VR like moving below the surface and provides strategies to render line traces from the players hands. 

The teleportation level is located at [Content/CesiumVRTutorial/Teleportation/Teleportation.umap](Content/CesiumVRTutorial/Teleportation/Teleportation.umap)

### :two: Tutorial 2 - Movement

In the second tutorial we explore motion across the world while minimizing nausea and how to keep the ground below the player loaded at all times. We also cover ways to change your movement speed based on the pawn's altitude, which aids in traversing great distances quickly and easily.

The movement level is located at [Content/CesiumVRTutorial/Movement/Movement.umap](Content/CesiumVRTutorial/Movement/Movement.umap)

### :three: Tutorial 3 - Vignette

In the third tutorial we explore applying a vignette over the user's view in order to reduce motion sickness. This vignette is callable from external components to activate from specific actions such as teleportation and snap rotation. The vignette component also automatically calculates an optimal vignette based on the user's movement velocity, ensuring that if the user's pawn is moving at all a vignette will be activated.

The vignette level is located at [Content/CesiumVRTutorial/Vignette/Vignette.umap](Content/CesiumVRTutorial/Vignette/Vignette.umap)

### :four: Tutorial 4 - Build for Quest

In the Meta Quest build tutorial we cover some topics on optimization as well as Android packaging and sdk setup.

The Build For Quest level is located at [Content/CesiumVRTutorial/BuildForQuest/BuildForQuest.umap](Content/CesiumVRTutorial/BuildForQuest/BuildForQuest.umap)

### :five: Tutorial 5 - Dragging the Globe

In the dragging the globe tutorial, the player can scale up to a size larger than the Earth to grab it and rotate it at any angle. While in the "Earth View" mode facilitated by an Earth Viewer component, the player can freely look towards the earth and rotate it with the thumbsticks as they please. This functionality is integrated into the main level by entering Earth View mode automatically when the player flyes above a certain altitude. The player can then leave "Earth View" and return to "Normal View" by teleporting onto the Earth's surface.

The dragging the globe level is located at [Content/CesiumVRTutorial/DraggingTheGlobe/DraggingTheGlobe.umap](Content/CesiumVRTutorial/DraggingTheGlobe/DraggingTheGlobe.umap)

### :six: Tutorial 6 - Metadata and Dynamic UI

The player can query tilesets for metadata and have the results show up in a UI that scales according to player distance and rotates to face the player, ensuring legibility from any distance.

The metadata and dynamic UI level is located at [Content/CesiumVRTutorial/DynamicUI/DynamicUI.umap](Content/CesiumVRTutorial/DynamicUI/DynamicUI.umap)

## :building_construction: Contribute to the repository

Please consult the [ContributionGuide.md](ContributionGuide.md)

## :mailbox_with_mail: Tell Us What You Think

Have you noticed a bug or fatal error? Open an issue [here](https://github.com/CesiumGS/cesium-unreal-vr-tutorial/issues).

Have any suggestions or questions? Ask them on the [community forum](https://community.cesium.com), we would love to hear from you.

## :green_book:License

[Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0.html). Cesium for Unreal VR Tutorials are free to use as a starter project for both commercial and non-commercial use.
