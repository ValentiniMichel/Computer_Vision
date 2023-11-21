# Computer_Vision
Valentini Michel's exam project of Computer Vision about camera pose estimation in a 3d model. 
First step is take images from the environment to reconstruct, upload images in Zephyr and create the 3d model. 

 <p align="center">
   <img src="docs/Immagine.png">
 </p>

 
Then, export the mesh, texture and camera parameters in a folder used by Blender where has been wrote a script to upload the mesh and camera parameters in a new scene matching the camera's attribute in Zephyr with Blender's attribute.

Here, a camera has been created for each camera parameters file from Zephyr, and the values for focal length, sensor width, height, the shift on x and y, and finally, the camera's position and rotation have been correctly set with Blender's world.

 <p align="center">
   <img src="docs/Immagine2.png">
 </p>
At the end is be add objects like a sphere in the scene to create a example of virtual reality. The animation was made possible by adding physics in Blender to both objects, allowing for collisions between the two objects, the mesh, and the ball.

 <p align="center">
   <img src="docs/Immagine1.png">
 </p>

Here is show the final result about two different cameras in different position and rotation that display the animation: 
<div style="display: inline-block; margin-right: 10px;">
  <img src="https://github.com/ValentiniMichel/Computer_Vision/blob/main/docs/ezgif.com-video-to-gif%20(1).gif" width="400" height="300">
</div>

<div style="display: inline-block;">
  <img src="https://github.com/ValentiniMichel/Computer_Vision/blob/main/docs/ezgif.com-video-to-gif.gif" width="400" height="300" >
</div>

In order to achieve a convincing augmented reality effect, we incorporate the original image (the one used to construct the 3D object) at the conclusion. This image is placed as the background in the camera view. Subsequently, the 3D object is removed, leaving only the animation superimposed on the original image. The outcome is a virtual animation seamlessly integrated into a real image, delivering the anticipated result akin to virtual reality.

<div style="display: inline-block;">
  <img src="https://github.com/ValentiniMichel/Computer_Vision/blob/main/docs/6rvyz.gif" width="400" height="300" >
</div>

<div style="display: inline-block;">
  <img src="https://github.com/ValentiniMichel/Computer_Vision/blob/main/docs/86rw2c.gif" width="400" height="300" >
</div>

<div style="display: inline-block;">
  <img src="https://github.com/ValentiniMichel/Computer_Vision/blob/main/docs/86rw4f.gif" width="400" height="300" >
</div>

<div style="display: inline-block;">
  <img src="https://github.com/ValentiniMichel/Computer_Vision/blob/main/docs/86rw6a.gif" width="400" height="300" >
</div>
 
# Run code
To running the project easily copy the repository in a folder, then execute the file "video_model_gravity.blend" and modify the path of cameras parameters correctly. 
