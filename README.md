![PixelVitaLogo](https://user-images.githubusercontent.com/20092823/113035584-09c89c80-919c-11eb-9a82-a0cc51e6c6f0.png)

# Vita Bilinear
Simple taiHEN plugin for PlayStation Vita that overrides texture sampling.   
This is a one-word-changed fork of [Vita-Nearest-Neighbour](https://github.com/MuxaJlbl4/Vita-Nearest-Neighbour), made specifically to address the unfiltered textures in Chaos Rings and Chaos Rings Omega.

## Showcase
WIP?

## Usage
1. Download and put **[VitaBilinear.suprx](https://github.com/swosho/Vita-Bilinear/releases)** into your **tai** folder  
2. Create ***TITLE_ID** section to choose only specific game. For example, **Chaos Rings I**:
```
*PCSG00497
ux0:tai/VitaBilinear.suprx
```
See **[taihen-parser repo](https://github.com/DaveeFTW/taihen-parser)** for more info  
3. **Reload taiHEN config.txt** from settings app or restart your Vita  

## Building
Requires **[Vita SDK](https://vitasdk.org)**  
Compile with:

```
cmake CMakeLists.txt  
make
```
