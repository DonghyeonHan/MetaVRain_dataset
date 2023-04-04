# Synthetic_MetaVRain_Dataset
This dataset named as 'Synthetic MetaVRain Dataset (SMD)' is adopted by MetaVRain project (ISSCC'2023, entitled "MetaVRain: A 133mW Real-time Hyper-realistic-3D-NeRF Processor with 1D-2D Hybrid-Neural-Engines for Metaverse on Mobile Devices").

The custom dataset named as "MetaVRain_dataset" consists of fourteen 3D models.

This dataset is made by using blender software and the dataset seems similar with synthetic NeRF/NSVF dataset.

The only difference is that it includes 3D models obtained from famous movie or animation.

The dataset consists of 14 models as follows: (This gif file is obtained by using MetaVRain)
1) deathwing
<img width="25%" src="https://github.com/DonghyeonHan/MetaVRain_dataset/blob/main/rendering%20example/deathwing.gif"/>
2) gundam2
<img width="25%" src="https://github.com/DonghyeonHan/MetaVRain_dataset/blob/main/rendering%20example/gundam.gif"/>
3) hooh
<img width="25%" src="https://github.com/DonghyeonHan/MetaVRain_dataset/blob/main/rendering%20example/hooh.gif"/>
4) ironman
<img width="25%" src="https://github.com/DonghyeonHan/MetaVRain_dataset/blob/main/rendering%20example/ironman.gif"/>
5) lapras
<img width="25%" src="https://github.com/DonghyeonHan/MetaVRain_dataset/blob/main/rendering%20example/lapras.gif"/>
6) lucario
<img width="25%" src="https://github.com/DonghyeonHan/MetaVRain_dataset/blob/main/rendering%20example/lucario.gif"/>
7) mario
<img width="25%" src="https://github.com/DonghyeonHan/MetaVRain_dataset/blob/main/rendering%20example/mario.gif"/>
8) mewtwo
<img width="25%" src="https://github.com/DonghyeonHan/MetaVRain_dataset/blob/main/rendering%20example/mewtwo.gif"/>
9) pikachu
<img width="25%" src="https://github.com/DonghyeonHan/MetaVRain_dataset/blob/main/rendering%20example/pikachu.gif"/>
10) ponyta
<img width="25%" src="https://github.com/DonghyeonHan/MetaVRain_dataset/blob/main/rendering%20example/ponyta.gif"/>
11) sonic
<img width="25%" src="https://github.com/DonghyeonHan/MetaVRain_dataset/blob/main/rendering%20example/sonic.gif"/>
12) spaceship
<img width="25%" src="https://github.com/DonghyeonHan/MetaVRain_dataset/blob/main/rendering%20example/jet.gif"/>
13) squid_game_doll
<img width="25%" src="https://github.com/DonghyeonHan/MetaVRain_dataset/blob/main/rendering%20example/squid.gif"/>
14) zealot
<img width="25%" src="https://github.com/DonghyeonHan/MetaVRain_dataset/blob/main/rendering%20example/zealot.gif"/>

The dataset can be used with simple code which is provided by the other general NeRF related software
such as https://github.com/creiser/kilonerf.

We also attached example code of loading the dataset as file, load_blender.py 

Followings are NeRF-based 3D Rendering results obtained by using our processor, MetaVRain.

|#|3D Model|V100 PSNR|MetaVRain PSNR|V100 SSIM|MetaVRain SSIM|
|--|------|------|------|------|------|
|1|deathwing|35.72|34.69|0.982|0.981|
|2|gundam2|33.43|33.17|0.970|0.969|
|3|hooh|34.13|33.36|0.982|0.981|
|4|ironman|30.28|30.05|0.971|0.971|
|5|lapras|38.64|37.96|0.990|0.990|
|6|lucario|37.27|36.20|0.990|0.990|
|7|mario|36.49|35.66|0.987|0.987|
|8|mewtwo|41.44|40.40|0.994|0.994|
|9|pikachu|37.78|37.07|0.987|0.987|
|10|ponyta|41.31|40.58|0.992|0.992|
|11|sonic|39.11|38.10|0.990|0.990|
|12|spaceship|34.88|34.76|0.984|0.984|
|13|squid_game_doll|41.01|39.61|0.996|0.995|
|14|zealot|30.14|29.83|0.961|0.96|

You can see the related demonstration video (MetaVRain, ISSCC'23) from YouTube: https://youtu.be/m-aqnZhALv0
