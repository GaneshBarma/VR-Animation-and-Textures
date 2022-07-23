- 3D Rendering with Animation and VR Application

- Execution:

- The program can execute on any brower that supports WebGL & THREE.js
- It can also be run by installing the live-server extension in VS Code and opening it through it. 

-File Structure
	- index.html - It contains the source code.
	- style.css - It contains the css code.
	- app.js - This is the main javascript code which contains the implementation of the application.
	- Texture.js - Contains the code for textures.
	- Train.js - contains the code to create a 3d train object.
	- Character Folder - This contains all the necessary files to show a 3D avatar.
	- js folder - This contains of javascript file which has the gui controls.

- Functionalities/Features:
	- Scene and animation
		- The scene initially contains a train, train Track, and road. We can use avatar gui button to spawn avatar in the scene.
		- The train head is the leader. It is a group which contains all other parts like cabins which follows the train.
		- Avatar can translate using the arrow keys.
		- By clicking the stick option in the gui controls, when the bounding box of avatar and train intersect, then avatar will stick to the train.
		- While sticking, avatar can jump, by clicking the 'K' key. 
	- Appearance and Textures
		- The scene has road, grass, track, cube and cylinder objects with texture some of planar geometru and some are circular geometry.
		- If we click the cylindrical mapping button, then the texture on cylinder will be changes to cylindrical texture.
		- If we click the sphercial mapping button, then the texture on spherical will be changes to spherical texture mapping.
	- Lighting
		- There are 3 sets of lights.
		- If we click street lights button, then the street lights will be activated on the roads.
		- If we	click track street button, then the lights on the track will be activated.
		- If we click headlight button, then headlight of train will be activated.
	- Camera
		- There are two different camera views.
		- First one is default view, where we can see the whole scene.
		- By clicking the droneviewer button, the view changes to drone mode, where we can conrol the camera by keyboard keys.
-References:
	1) https://threejs.org/docs/index.htmlmanual/en/introduction/Creatinga-scene
	2) https://threejsfundamentals.org/threejs/lessons/threejsscenegraph.html
	3) https://stackoverflow.com/questions/20774648/three-jsgenerate-uv-coordinate	
	4) https://www.cgtrader.com/free-3d-models/avatar - Used
for avatar 3d model 	
