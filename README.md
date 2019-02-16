# monitoringEngine_reactJs_threeJs
Monitoring engine which use reactJs, threeJs, nodeJs, es6 script technology for factory, warehouse 

# what is monitoring engine?
If you want to develope for monitor application for warehouse system containing various equipment (conveyor belt, agv, sorter, goods storage equipment etc...) your monitor application can call api which provided by this engine.
This engine can compitable with theeJs thechnology. And thie means you can olny load pre-built model (JSON) to this engine.

# API which sould be provided
1.  load
2.  add event callback (click event, drag and drop event, right clieck event, etc...)
3.  add object, remove object (object prototype should be provided)
4.  add object user data, update object user data
5.  find object by id, search object list (by name, by area)
6.  show object (object group), hide object (hide object)
7.  blink object (object group)
8.  change object (object group) color
9.  move object (object group)
10. blink object (object group)
11. turn on object tooltip / turn off object tooltip
12. show object name / hide object name
13. fix screen / unfix screen
14. magnify scene
15. capture scene shot
16. preset management (add preset, goto preset, remove preset, update preset, list preset)
17. animate (pre-defined 2 ~ 3 kind of animation)

# How to use
1. Make model which you want to monitor using tool like three.js editor, blender, schech up or autodesk)
   -> If you use blender, schech up or autodesk you can extract its model as extension .dae file then import it into three.js editor and then you can modify and extract it to file extension json.
   -> Three are two kind of three.js editors (web appliation and windows based program) which has same functionality.
2. In your monitor application
   -> let engine = new MonEngine('myMonitor');
   -> engine.load('my json file');
   -> you can use this engine using above api
   
# Install
you can install this package with below command.
- npm --save install monengine-react-three
