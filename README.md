[![Cesium for Unreal Logo](Images/Cesium-for-Unreal-Logo-WhiteBGH.jpg)](https://cesium.com/unreal-marketplace?utm_source=cesium-unreal&utm_medium=github&utm_campaign=unreal)

# Cesium VR Tutorial Series

The [Cesium for Unreal VR Tutorial Series]() covers strategies and solutions for several common challenges that come with building global-scale applications in VR using [Cesium for Unreal](https://www.unrealengine.com/marketplace/en-US/product/87b0d05800a545d49bf858ef3458c4f7). 

This repository holds example levels and code for all the features described in the [tutorial](). This series serves as a guide for recommend practices for VR application design and user ergonomics you can use in your projects. Each tutorial will describe the UX challenge, our design thinking, and the Blueprint code for each feature. 

<p align="center">
<img src="Images/Cesium-VR-Headset.jpg" alt="Cesium VR Headset"/>
</p>

### :rocket: Get Started

You will need to download the [Cesium for Unreal plugin from the Unreal Engine Marketplace](https://cesium.com/unreal-marketplace?utm_source=cesium-unreal&utm_medium=github&utm_campaign=unreal).

If you are new to the Cesium For Unreal plugin, check out the [Quickstart](http://cesium-dev.s3-website-us-east-1.amazonaws.com/cesium.com-next/prismic-releases/YnRNYBAAACIAms_B/learn/unreal/unreal-quickstart/) tutorial.

### 🎮:  VR Device Compatibility
We tested the inputs used in this project on Meta Quest 2, and are confident the inputs will work with Meta Quest and Rift devices using the Touch controllers. We have added reasonable corresponding inputs for other VR headsets such as the HTC Vive and Valve Index, but have not tested them. If you use any of these headsets, we'd love to get your feedback and build it into the tutorials.

If you are using a VR headset not mentioned above, please add the corresponding bindings for your controller for each input action / axis. For more information on setting up inputs, see the [Unreal Engine docs](https://www.unrealengine.com/en-US/blog/input-action-and-axis-mappings-in-ue4). For an example of setting up inputs across different VR devices, see the [VR Template](https://docs.unrealengine.com/4.27/en-US/Resources/Templates/VRTemplate/) project.

## 🗺️: Tutorial Descriptions

The features in this Unreal Engine Project are separated into individual levels with each level corresponding to a single tutorial. Each level builds upon the previous levels. If you would like to see a singular feature in action, open the level within the tutorial's corresponding folder to try it out. Open the level within the "Main" folder if you would like to see all of the features combined into one experience. 

### :one: Tutorial 1 - Teleportation, Line Traces, and Height Correction

In the first tutorial we cover teleporting the player long distances across the world and fetching higher levels of detail on 3D Tiles from a distance. This tutorial also covers common issues in VR like moving below the surface and provides strategies to render line traces from the players hands. 

The teleportation level is located at [Content/Teleportation/Teleportation.umap](blob/main/Content/Teleportation/Teleportation.umap)

### :two: Tutorial 2 - Movement

In the second tutorial we explore motion across the world while minimizing nausea and how to keep the ground below the player loaded at all times. We also cover ways to change your movement speed based on the pawn's altitude, which aids in traversing great distances quickly and easily.

The movement level is located at [Content/Movement/Movement.umap](blob/main/Content/Movement/Movement.umap)

### 📫:Tell Us What You Think

Have you noticed a bug or fatal error? Open an issue [here](https://github.com/CesiumGS/cesium-unreal-vr-tutorial/issues).

Have any suggestions or questions? Ask them on the [community forum](https://community.cesium.com), we would love to hear from you.

### :green_book:License

[Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0.html). Cesium for Unreal Samples is free to use as starter project for both commercial and non-commercial use.
