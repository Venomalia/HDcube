# HDcube
This is an [ESRGAN](https://github.com/xinntao/ESRGAN) model trained specifically for upscaling GameCube and Wii textures, but it can of course be used for other textures from that period.

It can be used for all image formats supported by Gamecube and Wii hardware and can remove its typical artifacts like
CMPR Block Compression (DXT1 algorithm, also known as BC1), color palette errors, color reduction up to 8bit color depth and 1bit alpha depth.

## Usage
I recommend [chaiNNer](https://github.com/chaiNNer-org/chaiNNer), which offers a graphical user interface and is based on a node system that can be used to solve very simple as well as very complex tasks effectively by "chaining" nodes together.
You get the best quality if you upscale the alpha channel [separately](https://i.imgur.com/KLqjupn.png).

## Image comparison

|GameCube|HDCube 3|GameCube|HDCube 3|
|---|---|---|---|
|<img src="https://i.imgur.com/476bdeZ.png" width="256"/>|<img src="https://i.imgur.com/wYESlsV.png" width="256"/>|<img src="https://i.imgur.com/7GGgStJ.png" width="256"/>|<img src="https://i.imgur.com/euMrBE5.png" width="256"/>|
|<img src="https://i.imgur.com/HxYcYN4.png" width="256"/>|<img src="https://i.imgur.com/GT9RjVc.png" width="256"/>|<img src="https://i.imgur.com/Bz39avz.png" width="256"/>|<img src="https://i.imgur.com/jXX6lhG.png" width="256"/>|
|<img src="https://i.imgur.com/R34f0Jv.png" width="256"/>|<img src="https://i.imgur.com/heetXP2.png" width="256"/>|<img src="https://i.imgur.com/U2DXTH5.png" width="256"/>|<img src="https://i.imgur.com/XZ8x19N.png" width="256"/>|
