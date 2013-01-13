TexturePacker
=============

Small C# app that packs all the png from a folder int a set of square atlas textures

Usage: TexturePacker -sp xxx -ft xxx -o xxx [-s xxx] [-b x] [-d]
          -sp | --sourcepath : folder to recursively scan for textures to pack
          -ft | --filetype   : types of textures to pack (*.png only for now)
          -o  | --output     : name of the atlas file to generate
          -s  | --size       : size of 1 side of the atlas file in pixels. Default = 1024
          -b  | --border     : nb of pixels between textures in the atlas. Default = 0
          -d  | --debug      : output debug info in the atlas

Ex: TexturePacker -sp C:\\Temp\\Textures -ft *.png -o C:\\Temp\atlas.txt -s 512 -b 2 --debug
