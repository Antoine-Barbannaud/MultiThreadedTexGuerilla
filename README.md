# MultiThreaded Tex Converter for Guerilla

Increase in performance → 80% on average

|                | Single Threaded |    MultiThreaded|
|----------------|-------------------------------|-----------------------------|
|16 textures, 80 MB| 54.63s |9.91s (tested on 16 threads with Ryzen 7 1700)
|188 textures in 4K, 7 GB |40 mins          | 9mins (tested on 8 threads with i7 4770HQ)     

After a while, it seems the bottleneck becomes the disk write speed and not conversion speed.

> Note that currently, this tool converts all textures to .tex and not only new versions. Soon I will push a script to execute within Guerilla that will take this into account. 

# Installation

- Download the archive as `.zip`, extract and run the `.exe` !

- Specify the guerilla installation folder\
For example: `S:/Documents/Guerilla2.3.26`
