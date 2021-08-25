![PixelVitaLogo](https://user-images.githubusercontent.com/20092823/113035584-09c89c80-919c-11eb-9a82-a0cc51e6c6f0.png)

# Vita Bilinear
A simple taiHEN plugin for PlayStation Vita that overrides texture sampling.   
This is a one-word-changed fork of [Vita Nearest Neighbour](https://github.com/MuxaJlbl4/Vita-Nearest-Neighbour), made specifically to address the unfiltered textures in Chaos Rings and Chaos Rings Omega. Could be useful for other games.

## Showcase
![CRI-1](https://user-images.githubusercontent.com/5187034/127921982-c1cbfa7a-ca26-4c70-98a0-41b66b081e71.gif)
![CRI-2](https://user-images.githubusercontent.com/5187034/127922049-0cc6167c-8ed2-45cc-85f1-ec2b39efab96.gif)

## Usage
1. Place **[VitaBilinear.suprx](https://github.com/swosho/Vita-Bilinear/releases)** into your **tai** folder  
2. Add a ***TITLE_ID** section to your **ux/ur0:tai/config.txt** to choose a specific game. For example, **Chaos Rings I** and **Chaos Rings Ω**:
```
*PCSG00497
ux0:tai/VitaBilinear.suprx
*PCSG00499
ux0:tai/VitaBilinear.suprx
```
See **[taihen-parser repo](https://github.com/DaveeFTW/taihen-parser)** for more info  
3. **Reload taiHEN config.txt** from HENkaku Settings in the Settings app or reboot your Vita  

## Building
Requires **[Vita SDK](https://vitasdk.org)**  
Compile with:

```
cmake CMakeLists.txt  
make
```
