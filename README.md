# MetaVRain_dataset
This is custom dataset adopted by MetaVRain (ISSCC'2023, entitled "MetaVRain: A 133mW Real-time Hyper-realistic-3D-NeRF Processor with 1D-2D Hybrid-Neural-Engines for Metaverse on Mobile Devices")

The custom dataset named as "MetaVRain_dataset" consists of fourteen 3D models.

This dataset is made by using blender software and the dataset seems similar with synthetic NeRF/NSVF dataset.

The only difference is that it includes 3D models obtained from famous movie or animation.

The dataset consists of 14 models as follows: 
1) deathwing
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
|2|gundam2|33.73|35.72|0.977|0.982|
