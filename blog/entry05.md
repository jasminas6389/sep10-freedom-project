# Entry 5
##### 4/20/26

### Content
My tool I learned is A-frame, A-frame is really easy to work with, you can use it to make 3D-models of anything you need. You can change the background, the sky color, the floor color, you can even include your own picture that you would like for it to be.  

### What I learned
Learning my tool was easy for me because I watched multiple videos about A-frame, and it taught me: 
* Position: Lets me move objects to different spots in the scene using x, y, and z coordinates, like moving things forward, sideways, or up and down.
* Rotation: Changes how objects tilt or spin around, like making them lean forward or turn left.
* Size: Adjusts how big or small shapes are by changing width, height, or radius.  
* Colors and textures: I can add colors or pictures to make things look more real or cool.  
* Controls: Using WASD, I can walk around the scene and look around the model.
* -  `<a-entity camera look-controls wasd-controls="acceleration:100" position="0 1.6 0"></a-entity>` this is the code to paste in. You can change the position on where the start for the controls is. 
* `<a-sky color= "color">` changes the background or sky to any color I choose.  
* `<a-plane color= "color"> `creates the ground, but if I only use this, the ground might not show up unless I zoom out because it has no position, size, or rotation set.  
* To see the ground clearly, I need to add position, width, height, and rotation attributes, like this: `<a-plane color= "color" position= "x y z" width= "value" height= "value" rotation= "x y z">.  `
* I can also use images for the sky, but they need to wrap all around 360 degrees; otherwise, there will be a visible line where the images connect.
* When making the ground you can also use pictures, but you may have to use more than one. Such as adding "repeat" in your code, so the one picture you picked won't be blurry trying to take up the whole space.
* You can add pictures of a brick pattern, and if you want it to be smaller you can increase the number with the repeated pictures.
* You can set the background picture to be anything, even Batman.


### How I learned
I used these websites to help me learn more about A-frame.
* https://aframe.io/docs/1.7.0/introduction/
* https://github.com/aframevr/aframe/tree/gh-pages?tab=readme-ov-file
* https://aframe.io/docs/1.5.0/components/geometry.html#triangle

https://docs.google.com/document/d/1yyJBjTm3WnLY-VKRO6XZOexINkYZcMQA02Mb7VDdpR0/edit?tab=t.0#heading=h.n30f2ck5cvau




### Skills



[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
