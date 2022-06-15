# Matterport to Unreal Engine
![download](https://user-images.githubusercontent.com/81708456/173877557-8a63ee46-a522-4f19-bd2a-ace998aeb209.png)
![download](https://user-images.githubusercontent.com/81708456/173877737-a3052618-251c-4eff-a8ab-027d65c82adf.png)

## Purpose Statement & Setup

In this repository, we are taking a Matterport scan in the .glTF file format and converting it into an Unreal Engine experience. For Unreal Engine the necessary plugin(s):

![Capture2](https://user-images.githubusercontent.com/81708456/173877290-c427d838-978e-4091-8501-5f17568c3ece.PNG)

https://www.unrealengine.com/marketplace/en-US/product/gltf-exporter

To install simply open up the Unreal Engine editor and then add the plugin to your existing project plugins. Then you are ready to iport the Unity file from the matterport scan folder. In this repository there are two folders: 

![Capture1](https://user-images.githubusercontent.com/81708456/173877264-9ccf165b-51a9-474b-abce-9288d4bb6c2a.PNG)

Matterport_To_Unreal_Engine/matterport_example
Matterport_To_Unreal_Engine/matterport_in_unreal

The first folder will hold the Matterport example scan and the second folder holds the Unreal Engine experience with the Matterport imported. If you load the experience from the matterport_in_unreal folder, you will have to navigate to the matterport folder within the project, select all of the textures and obj files, and then drag/drop to the stage. Once this is done, build the environment and the lighting. In this case, there will need to be lighting implemented throughout the scan but that is a relatively quick process. This repository is a proof of concept pipeline for matterport scan uploads. In the future this library will be able to create matterport scans in Unreal Engine and then use ML and DL to fix textures, scaling, and lighting. 
