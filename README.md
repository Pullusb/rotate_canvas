# Rotate canvas

Blender addon - Canvas rotation shortcut for both free and camera view

**[Download latest](https://github.com/Pullusb/rotate_canvas/archive/master.zip)**

---  

## Description


![demo canvas rotate gif](https://raw.githubusercontent.com/Pullusb/images_repo/master/RC_rotate_canvas_demo_view_and_cam.gif)

Customise shortcut in addons preferences, Default `ctrl + alt + right-Click`.  
Shortcut changed are refreshed upon modifications.

![preferences canvas rotate gif](https://raw.githubusercontent.com/Pullusb/images_repo/master/RC_rotate_canvas_pref_shortcut.png)

**Use Hud**: Show angle value and lines.

**Reset view** (free navigation only): Click and release immediately without rotation to reset (up view point to world Z).

<!-- OpenGL drawing can be enabled by passing `self.hud` to True in the invoke of the operator (mainly used for debugging). -->


Original base script by [Jum on stackexchange](https://blender.stackexchange.com/questions/136183/rotating-camera-view-in-grease-pencil-draw-mode-in-blender-2-8), Heavily modified to work in both view and camera with rotate axis method suggested by [Christophe Seux](https://gitlab.com/ChristopheSeux).


## Changelog:

1.0.3:


- Added addon-prefs option to enable HUD
- demo gifs and images

1.0.2:

- Added free view reset (up point to world Z) on quick clic and release.
- Hud turned Off

1.0.1:

- First working version without ortho bugs