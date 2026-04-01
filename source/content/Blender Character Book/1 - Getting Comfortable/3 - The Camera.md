You have a few options for how to tackle navigating the scene in Blender.
## Middle Mouse Navigation
The primary way I personally control the camera in Blender is with the middle mouse button (MMB):

- `Drag MMB` orbits.
- `Shift + Drag MMB` pans.
- `Ctrl + Drag MMB` or scrolling the wheel zooms.
- `Alt + Click MMB` recenters the camera where you clicked.
- `Alt + Drag MMB` works in two ways:
	- Drag MMB first, then hold Alt: orbit the camera, snapping to key points as you near them.
	- Hold Alt, flick the mouse, and press MMB: Quickly snaps the camera to side/top/bottom views. I use this extensively, but it may not be natural to everyone. 
## Numpad Navigation
If you have a numpad, you can use these controls. If you don't, there is an option you can enable to make the main keyboard keys mimic these functions:
![[Pasted image 20260331111807.png]]

- `5`: Toggle [[#Perspective and Orthographic]]
- Cardinal directions: orbit camera
- Diagonal directions: snap to side/top views
- `+` and `-`: zoom
- `.`: focus on selection
- `/`: isolate selection / restore previous view
- `0`: view through active camera

The last three options here are particularly useful, so you may wish to toggle on 'Emulate Numpad' if you do not have one.
## The Gizmo
In the upper right of the 3D viewport, you'll see this thing:
![[Pasted image 20260331112310.png]]
- By clicking and dragging on the axis ball, you can orbit the camera.
- Clicking any of the axis label circles will snap to that view.
- Click and hold the magnifying glass to zoom.
- Click and hold the hand to pan.
- Click the camera to view through the active camera.
- Click the grid to toggle [[#Perspective and Orthographic]]
	- When viewing through the camera, the grid changes to a lock icon. This will let you use your camera controls to move the camera object.
## Perspective and Orthographic
If you're not familiar with these terms, in a perspective camera things that are farther away are smaller, while in an orthographic one everything is the same size. Orthographic view is most useful when the camera is snapped to the sides or top of the scene, giving us a 'blueprint view.'
![[Pasted image 20260331113810.png]]
## Walking and Flying
You can also navigate the camera WASD style. Press `Shift-Tilde` to enable this.
* `WASD` moves
* `E` and `Q` raise and lower you
* Mouse aims
* `Shift` speeds up and `Alt` slows down
* `Space`teleports you to where the crosshairs are pointed
* `Tab` toggles gravity. Beware, the grid plane doesn't count as solid ground! You need some geometry to stand on.
