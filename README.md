# GoFeaGUI
Graphical user interface for GoFea

First window is splash windows

```
Main window:
+----------------------------------------+
|             North                      |
+----------------------------------------+
|         |                    |         |
| West    |    Center          | East    |
|         |                    |         |
|         |                    |         |
|         |                    |         |
|         |                    |         |
|         |                    |         |
+----------------------------------------+
|             South                      |
+----------------------------------------+
```

Description:
- [Splash](https://github.com/Konstantin8105/GoFeaGUI/blob/master/Splash.md )
- [North](https://github.com/Konstantin8105/GoFeaGUI/blob/master/North.md )
- [Center](https://github.com/Konstantin8105/GoFeaGUI/blob/master/Center.md )
- [West](https://github.com/Konstantin8105/GoFeaGUI/blob/master/West.md )
- [East](https://github.com/Konstantin8105/GoFeaGUI/blob/master/East.md )
- [South](https://github.com/Konstantin8105/GoFeaGUI/blob/master/South.md )
> Note: 
> - flexibility border between center and west, center and east
> - tree view on West is flexibility and allowable collapse to border

Code modification windows

Future:
- mini git hystory of project
Cursor property on 3D view:
- Left button - rotate
- Roll - zoom
- Right button - hand moving 
- Left button click - Selection
- Left button click/window + Ctrl - add to selection
- Left button click/window + Shift - select in windows
- Left button click + Alt - Smart selection
- Assembly tree view


MVC (model-controller-view):
* **Model** - golang server
* **Controller** - js
* **View** - js

Connect between js and golang server - WebSocket, json

```
+--------------------+
| Frontend:          |
| javascript         |
| threejs            |
| qooxdoo            |
+--------------------+
      |   /\
      |    | json
      V    |
+--------------------+
| Backend            |
| golang             |
+--------------------+
```
