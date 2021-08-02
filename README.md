![PixelVitaLogo](https://user-images.githubusercontent.com/20092823/113035584-09c89c80-919c-11eb-9a82-a0cc51e6c6f0.png)

# Vita Bilinear
Simple taiHEN plugin for PlayStation Vita that overrides texture sampling.
This is a one-word-changed fork of [Vita-Nearest-Neighbour](https://github.com/MuxaJlbl4/Vita-Nearest-Neighbour), made specifically to improve image quality of the early Chaos Rings titles, all of which utilise point filtering.

## Showcase
WIP

## Usage
1. Download and put **[VitaBilinear.suprx](https://github.com/swosho/Vita-Bilinear/releases)** into your **tai** folder  
2. Append ***ALL** section in **ux/ur0:tai/config.txt** with:
```
*ALL
ux0:tai/VitaBilinear.suprx
```
Or create ***TITLE_ID** section to choose only specific game. For example **Disgaea 3: Absence of Detention (Eu region)**:
```
*PCSB00098
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
