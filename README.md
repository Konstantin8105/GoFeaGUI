# GoFeaGUI
Graphical user interface for GoFea

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
- North  - menu, toolbar, tabs
- West   - tree view for model of inlet models, tabs
- Center - 3D view of model
- East   - tables, property
- South  - status bar, 1-line with short information
> Note: 
> - flexibility border between center and west, center and east
> - tree view on West is flexibility and allowable collapse to border

North. Toobar. View options:
- 2D
- 3D view:
	- XOY
	- XOY back side
	- XOZ 
	- XOZ back side
	- YOZ
	- YOZ back side
	- XYZ(3d view)
- 3D view:
	- Simple
	- Wireframe
	- Realistic
- 3D view:
	- Orthonal
	- Perspective
	- Virtual reality
- Rotate in windows local system:
	- XOY
	- XOY back side
	- XOZ 
	- XOZ back side
	- YOZ
	- YOZ back side

North. Toolbar. View options:
- Zoom "+"
- Zoom "-"
- Zoom all
- Zoom by window
- Hand

North toolbar. Create elements:
- New point
- New beam
- New plate
- Mirror elements
- Copy array
- Copy by circle

North toolbal. Cursor option:
- Simple cursor
- Smart cursor

North tabs (/ underline for - Center):
- Design / 3D model
- Text editor / Text
- Calculation process / Text
- Postprocessor / 3D model

West tabs with internal tabs (/ underline for - East), if North tab is Design:
- Overview / None
- Geometry:
	- Point / Table of points
	- Lines / Tables of points and lines
	- Plates / Tables of points and plates
- Property:
	- Shape / List of property
	- Material / List of property
	- Specific / List of property
	- Supports / List of property
	- Cases and loads / List of property / Center - Text
- Calculation:
	- Check code / List of property 
	- Allowable processors / List of property
	- Allowable computers / List of property

West tabs (/ underline for - East), if North tab = Postprocessor:
- Point
	- Displacement / Tabs for table displacement: cases, max/min
	- Reactions / Tabs for table reactions: cases, max/min, global
- Beam
	- Diagramm / None
	- Code ratio / None
- Plate
	- View / None

South. Label indocators:
- amount selected points
- amount points
- amount selected beams
- amount beams
- amount selected plates
- amount plates

South popup window:
- recommendations, warnings, errors - Text with separation by line

First splash window:
- Open lasts projects
- New project
- Generate project
- Performance test

Code modification windows

MENU OPTIONS

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
Assembly tree view



