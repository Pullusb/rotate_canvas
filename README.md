# Rotate canvas

Blender addon - Canvas rotation shortcut for both free and camera view

**[Download latest](https://github.com/Pullusb/rotate_canvas/archive/master.zip)**

---  

## Description

  
Customise shortcut in addons preferences, Default `ctrl + alt + right-Click`.  
Shortcut changed are refreshed at each modification)

**Free view only**: Click and release immediately without rotation to reset (up view point to world Z).

OpenGL drawing can be enabled by passing `self.hud` to True in the invoke of the operator (mainly used for debugging).


Original base script by [Jum](https://blender.stackexchange.com/questions/136183/rotating-camera-view-in-grease-pencil-draw-mode-in-blender-2-8), Heavily modified to work in both view and camera with rotate axis method suggested by [Christophe Seux](https://gitlab.com/ChristopheSeux).


## Changelog:

1.0.2:

- Added free view reset (up point to world Z) on quick clic and release.
- Hud turned Off

1.0.1:

- First working version without ortho bugs