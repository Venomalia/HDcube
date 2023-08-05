<img src="https://i.imgur.com/qpUjENn.png" width="400"/>

# HDcube
This is an [ESRGAN](https://github.com/xinntao/ESRGAN) model trained specifically for upscaling and restoration of GameCube and Wii textures, but it can of course be used for other textures from that period, like playstation 2, Xbox or PC games from that time.

It can be used for all image formats supported by Gamecube and Wii hardware and can remove its typical artifacts like
CMPR Block Compression (DXT1 algorithm, also known as BC1), color palette errors, color reduction up to 8bit color depth and 1bit alpha depth.

[<img src="https://img.shields.io/github/v/release/Venomalia/HDcube?label=HDcube&style=for-the-badge" alt="Release Download" height="34"/>](https://github.com/Venomalia/HDcube/releases/latest)

## Usage
I recommend [chaiNNer](https://github.com/chaiNNer-org/chaiNNer), which offers a graphical user interface and is based on a node system that can be used to solve very simple as well as very complex tasks effectively by "chaining" nodes together.
You get the best quality if you upscale the alpha channel [separately](https://i.imgur.com/KLqjupn.png).


## Image comparison

|GameCube|HDcube3|
|---|---|
|<img src="https://i.imgur.com/LF0HGBg.png" width="512"/>|<img src="https://i.imgur.com/vDWRaLs.png" width="512"/>|

|GameCube|HDCube 4|GameCube|HDCube 4|
|---|---|---|---|
|<img src="https://i.imgur.com/476bdeZ.png" width="256"/>|<img src="https://i.imgur.com/nIv5qBs.png" width="256"/>|<img src="https://i.imgur.com/7GGgStJ.png" width="256"/>|<img src="https://i.imgur.com/HRBTAYV.png" width="256"/>|
|<img src="https://i.imgur.com/U2DXTH5.png" width="256"/>|<img src="https://i.imgur.com/u8PWMpD.png" width="256"/>|<img src="https://i.imgur.com/R34f0Jv.png" width="256"/>|<img src="https://i.imgur.com/BFMiypi.png" width="256"/>|

[more...](https://github.com/Venomalia/HDcube/tree/main/v4#image-comparison)

## Model
|Scale|Name|Iterations|Architecture|Date|
|---|---|---|---|---|
|4|[HDcube4Compact](https://github.com/Venomalia/HDcube/tree/main/v4Compact)|400k|[Real-ESRGAN Compact](https://github.com/xinntao/Real-ESRGAN)|2023-06-26|
|4|[HDcube4Plus-B](https://github.com/Venomalia/HDcube/tree/main/v4)|600k|[Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN)|2023-06-19|
|4|[HDcube4-A](https://github.com/Venomalia/HDcube/tree/main/v4)|400k|[Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN)|2023-03-20|
|4|[HDcube4-B](https://github.com/Venomalia/HDcube/tree/main/v4)|500k|[Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN)|2023-03-20|
|4|[HDcube-Alpha](https://github.com/Venomalia/HDcube/tree/main/Alpha)|350k|[Real-ESRGAN Compact](https://github.com/xinntao/Real-ESRGAN)|2023-03-20|
|2|[HDcubeCompact](https://github.com/Venomalia/HDcube/tree/main/Compact)|500k|[Real-ESRGAN Compact](https://github.com/xinntao/Real-ESRGAN)|2023-02-09|
|4|[HDcube3](https://github.com/Venomalia/HDcube/tree/main/v3)|500k|[ESRGAN](https://github.com/xinntao/ESRGAN)|2022-12-13|
|4|[HDcube2](https://github.com/Venomalia/HDcube/tree/main/v2)|250k|[ESRGAN](https://github.com/xinntao/ESRGAN)|2022-05-31|
|4|[HDcube](https://github.com/Venomalia/HDcube/tree/main/v1)|200k|[ESRGAN](https://github.com/xinntao/ESRGAN)|2022-05-10|
