[![Cesium for Unreal Logo](Images/Cesium-for-Unreal-Logo-WhiteBGH.jpg)](https://cesium.com/unreal-marketplace?utm_source=cesium-unreal&utm_medium=github&utm_campaign=unreal)

In this tutorial series, we will cover solutions for several common challenges that come with building world-scale applications in VR using Cesium for Unreal. The features we build will follow VR best practices to give players a better and more comfortable experience. We hope that this series can serve as a guide for thinking about VR design and user ergonomics in your own projects.

This tutorial will describe the UX challenge, our design thinking, and the Blueprint code for each feature. You can follow along from a blank project, or download the project files here to try them out yourself. Within each folder you will find a corresponding level which highlights a different feature. To see all features working together, open the main level located within the root content folder.

### Note on inputs
We tested the inputs used in this project on Meta Quest 2, and are confident the inputs will work with Meta Quest and Rift devices using the Touch controllers. We have added reasonable corresponding inputs for other VR headsets such as the HTC Vive and Valve Index, but have not tested them. Please let us know if there are any issues.

If you are using a VR headset not mentioned above, please add the corresponding bindings for your controller for each input action / axis. For more information on setting up inputs, see the [Unreal Engine docs](https://www.unrealengine.com/en-US/blog/input-action-and-axis-mappings-in-ue4). For an example of setting up inputs across different VR devices, see the [VR Template](https://docs.unrealengine.com/4.27/en-US/Resources/Templates/VRTemplate/) project.

<p align="center">
<img src="Images/Cesium-VR-Headset.jpg" width="50%" alt="Cesium VR Headset"/>
</p>

### :rocket: Get Started

You will need to download the [Cesium for Unreal plugin from the Unreal Engine Marketplace](https://cesium.com/unreal-marketplace?utm_source=cesium-unreal&utm_medium=github&utm_campaign=unreal).

Have questions? Ask them on the [community forum](https://community.cesium.com).

## :mountain: Tutorial Descriptions

### :one: Tutorial 1 - Teleportation, Line Traces, and Height Correction

In the first tutorial we cover teleporting the user across long distances on Cesium World Terrain, and enforcing higher levels of detail on 3D Tiles from a distance. This tutorial also covers common issues in VR like moving below the surface and provides strategies to render line traces from the players hands. 

### :two: Tutorial 2 - Movement

TBA

### :green_book:License

[Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0.html). Cesium for Unreal Samples is free to use as starter project for both commercial and non-commercial use.
