## Source Code 

VehicleX is based on [Unity](https://unity.com/). Here we released the whole [Unity project](https://drive.google.com/file/d/1vMqNhjTZmiFr9fAzU2HMWxqZ5-Fb_N_W/view?usp=sharing). [Background images](https://drive.google.com/open?id=11JQMzaF7tUOEjZXzgVbFUTDjpgD_6wTr) are also required. Once you download them the file structure should be like:

```
~
└───Source
    └───Assets
    │   │ Cars_folder
    │   │ ...
    │
    └───Background_imgs
    │   │ vdo (1).avi
    │   │ ...
    │
    └───Library
    │
    ...
```

[Unity hub](https://docs.unity3d.com/Manual/GettingStartedInstallingHub.html) is recommended to manage Unity projects. Please use Unity version 2019.3.0a8 or above. Once both the project and Unity editor are ready. The project can be opened easily by the Unity hub.    

![fig1](https://github.com/yorkeyao/VehicleX/blob/master/VehicleX/Unity_source/Images/unity_hub.PNG)  

## Image Generation by Unity Editor

* Open the project using Unity hub and you will see the interface below.
* Comment out line 30 and uncomment line 31 for Inference.py.  
* Run Inference.py and you will see a notice to press the play button. 
* Press the play button ▶️ in Unity Editor to get the images of Vehicles. 

![fig2](https://github.com/yorkeyao/VehicleX/blob/master/VehicleX/Unity_source/Images/interface.PNG) 

## Notice

* Please make sure the resolution of the game is 1920*1080. It can be controled in the game tab.
* If you see error CS1061: 'RawImage' does not contain a definition for 'm_Texture'. Please open this file and replace all content with ./Script/RawImage.cs.
* Due to copyright issues. We are only able to release part of vehilce models in source code. The build version has all vehicle models included.  


