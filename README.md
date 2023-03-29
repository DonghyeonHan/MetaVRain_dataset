# MetaVRain_dataset
This is custom dataset adopted by MetaVRain (ISSCC'2023, entitled "MetaVRain: A 133mW Real-time Hyper-realistic-3D-NeRF Processor with 1D-2D Hybrid-Neural-Engines for Metaverse on Mobile Devices")

The custom dataset named as "MetaVRain_dataset" consists of fourteen 3D models.

This dataset is made by using blender software and the dataset seems similar with synthetic NeRF/NSVF dataset.

The only difference is that it includes 3D models obtained from famous movie or animation.

The dataset consists of 14 models as follows: 
1) deathwing
<img width="50%" src="https://github.com/DonghyeonHan/MetaVRain_dataset/blob/main/rendering%20example/deathwing.gif"/>
2) gundam2
3) hooh
4) ironman
5) lapras
6) lucario
7) mario
8) mewtwo
9) pikachu
10) ponyta
11) sonic
12) spaceship
13) squid_game_doll
14) zealot

The dataset can be used with simple code which is provided by the other general NeRF related software
such as https://github.com/creiser/kilonerf.

We also attached example code of loading the dataset as file, load_blender.py 

Followings are NeRF-based 3D Rendering Results with our processor, MetaVRain.

|#|3D Model|V100 PSNR|MetaVRain PSNR|V100 SSIM|MetaVRain SSIM|
|--|------|------|------|------|------|
|1|deathwing|33.73|35.72|0.977|0.982|
|2|gundam2|32.37|33.43|0.965|0.970|
|3|hooh|-|-|34.13|0.982|
|4|ironman|29.14|30.28|0.965|0.971|
|5|lapras|-|-|38.64|0.990|
|6|lucario|-|-|37.27|0.990|
|7|mario|35.51|36.49|0.984|0.987|
|8|mewtwo|-|-|41.44|0.994|
|9|pikachu|34.42|37.78|0.980|0.987|
|10|ponyta|-|-|41.31|0.992|
|11|sonic|38.22|39.11|0.989|0.990|
|12|spaceship|-|-|34.88|0.984|
|13|squid_game_doll|36.40|41.01|0.991|0.996|
|14|zealot|28.78|30.14|0.952|0.961|

You can see the related demonstration video (MetaVRain, ISSCC'23) as YouTube: https://youtu.be/m-aqnZhALv0
