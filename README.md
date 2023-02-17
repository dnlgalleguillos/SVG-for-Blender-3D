## SVG-for-Blender-3D

### How to use SVG into Blender 3D

- [Inkscape](https://inkscape.org/) is a free and open-source vector graphics editor used to create vector images, primarily in Scalable Vector Graphics (SVG) format. Other formats can be imported and exported.

I will inform you about the protocol to import an SVG into blender 3D attaching the Inkscape and Blender files.

### Operating System and Software
### All this work are created with Linux Operating System and GNOME Desktop.

- Debian and Fedora
- GNOME Desktop
- Blender 3.5.0 Alpha
- Inkscape 1.2

License CC BY-SA 4.0

## Librsvg
- [Librsvg](https://github.com/GNOME/librsvg) a library to render SVG images to Cairo surfaces. GNOME uses this to render SVG icons. Outside of GNOME, other desktop environments use it for similar purposes. It is also used in Wikimedia to render the SVG images that appear in Wikipedia, so that even old web browsers can display them. Many projects which casually need to render static SVG images use librsvg.

## Protocols

To deploy this project run.
```bash
  Open Inkscape
```
Let's find the icons in this case they will be Adwaita.
```bash
  /usr/share/icons/Adwaita/
```
Select the icons you want, I'll leave you an SVG of the icons I chose.
```bash
  Background Icons.svg
```
Now we are going to open Blender to import SVG Scalable Vector Graphics formats.
```bash
  Open Blender
```
Import SVG from Blender
```bash
  File - Import - Scalable Vector Graphics (.svg)
```
Extrude SVG into Blender
```bash
  Edit Mode - Select all files - Click E - Now you can Extrude the SVG. 
```
Now you can use this SVG into Blender
```bash
  SVG Icons.blend
```
And this is the Final Render
- Render Engine: Cycles
- Feature Set: Experimental
- Add-ons: Node Wrangler




![alt text](https://github.com/dnlgalleguillos/SVG-for-Blender-3D/blob/main/Render%20SVG%20for%20Blender.png?raw=true "SVG for Blender 3D")
