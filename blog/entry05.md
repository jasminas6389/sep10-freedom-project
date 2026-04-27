# Entry 5
##### 4/20/26

### Content
My tool I learned is **A-frame**, A-frame is really easy to work with, you can use it to make 3D models of anything you need. You can change the background, the sky color, the floor color, you can even include your own picture that you would like for it to be. Using your own images makes it realistic. We were learning our tool by ourselves and we had a good month to learn everything we could to help us prepare for our freedom project that we are going to make. We have to include our tool in our project and how it can make it better.

### What I learned
Learning my tool was easy for me because I watched multiple videos about A-frame, and it taught me: 
* Position: Lets me move objects to different spots in the scene using x, y, and z coordinates, like moving things forward, sideways, or up and down.
* Rotation: Changes how objects tilt or spin around, like making them lean forward or turn left.
* Size: Adjusts how big or small shapes are by changing width, height, or radius.  
* Colors and textures: I can add colors or pictures to make things look more real or cool.  
* Controls: Using WASD, I can walk around the scene and look around the model.
* `<a-entity camera look-controls wasd-controls="acceleration:100" position="0 1.6 0"></a-entity>` This is the code to paste in. You can change the position on where the start for the controls is. 
* `<a-sky color="color">` changes the background or sky to any color I choose.  
* `<a-plane color= "color"> `creates the ground, but if I only use this, the ground might not show up unless I zoom out because it has no position, size, or rotation set.  
* To see the ground clearly, I need to add position, width, height, and rotation attributes, like this: `<a-plane color= "color" position= "x y z" width= "value" height= "value" rotation= "x y z">.  `
* I can also use images for the sky, but they need to wrap all around 360 degrees; otherwise, there will be a visible line where the images connect.
* When making the ground you can also use pictures, but you may have to use more than one. Such as adding "repeat" in your code, so the one picture you picked won't be blurry trying to take up the whole space.
* You can add pictures of a brick pattern, and if you want it to be smaller you can increase the number with the repeated pictures.
* You can set the background picture to be anything, even Batman.


### How I learned
I used these websites to help me learn more about A-frame.
* https://aframe.io/docs/1.7.0/introduction/ -A-frame website
* https://github.com/aframevr/aframe/tree/gh-pages?tab=readme-ov-file -A-frame GitHub repository
* https://aframe.io/docs/1.5.0/components/geometry.html#triangle -geometry shapes
* https://www.youtube.com/playlist?list=PLWkWuhMLkR7D_VSEMkj45NIgF8i2dlUce -I also watched multiple videos.
* https://docs.google.com/document/d/1yyJBjTm3WnLY-VKRO6XZOexINkYZcMQA02Mb7VDdpR0/edit?tab=t.0#heading=h.n30f2ck5cvau -my code for teleportation device.


#### Video Notes
* **AFrame Lesson 1.3: Color and material attribute. Sky and plane component.**
  - `<a-sky color= "blue"></a-sky>` will change the color of the background/sky into blue.
  - `<a-plane color= "brown"></a-plane>` if you only type this the ground will not be visible unless you zoom out because there is no coordinates, and the component is default rotated, so you need to add coordinates.
  - This is the code for making the ground. `<a-plane color= "brown" position= " _ _ _" width= "__" height= "__" rotation= "_ _ _ "></a-plane>`
  - You can use images for the sky, but it has to wrap fully around 360 degrees otherwise there will be a distinctive line where they both connect.
  - When making the ground you can also use pictures, but you may have to use more than one. Such as adding "repeat" in your code, so the one picture you picked won't be blurry trying to take up the whole space.
  - You can add pictures of a brick pattern, and if you want it to be smaller you can increase the number with the repeated pictures.

* **AFrame Lesson 1.4: Building models**
  - The order of components in code doesn't affect the position of the object.
  - Example: Building a snowman with three spheres of different sizes and positions:
  - Largest sphere at the bottom (radius larger, position lower).
  - Medium sphere in the middle.
  - Smallest sphere at the top.
  - `<a-entity>` acts as a container. like a `<div>`
  - You can use that to make multiple identical model and change the positions.


### What I made
I made several different models such as: 

_A house with a colored sky_
``` html
<a-sky color="lightblue"></a-sky>
<!-- ground -->
<a-plane position="0 0 -5" rotation="-90 0 0" width="50" height="50" color="green"></a-plane>
<!-- sun -->
<a-sphere position="0 25 -50" radius="5" material="color: yellow"></a-sphere>
<!-- base of house-->
<a-box position="5 2 -10" width="6" height="4" depth="6" color="#70444A"></a-box>
<!-- roof of house -->
<a-cone position="5 5.4 -10" radius-bottom="4" height="3" color="#B3505D"></a-cone>
<!-- Door -->
<a-box position="5 1 -7" width="1" height="2" depth="0.1" color="saddlebrown"></a-box>
<!-- Windows -->
<a-box position="3 2 -7" width="1.2" height="1.2" depth="0.1" color="#C3D4D0"></a-box>
<a-box position="7 2 -7" width="1.2" height="1.2" depth="0.1" color="#C3D4D0"></a-box>
<a-box position="4.6 1 -7" width="0.1" height="0.1" depth="0.1" color="white"></a-box>
<a-camera position="0 1.6 5"></a-camera>
```
Building the house wasn't too hard, but I had to make the windows aligned and place the door in the center. For the handle, I copied and pasted the window code, then just made it smaller in width and height to fit with the door.

_Then I made my finger scanning technology machine:_
```html
    <a-scene>

      <!--oval shapes -->
      <a-torus position="0 0 -10" radius="20" radius-tubular="0.02" color="black" segments-tubular="100" scale="1 1.5 1"></a-torus>
      <a-torus position="0 0 -10" radius="19" radius-tubular="0.02" color="black" segments-tubular="100" scale="1 1.5 1"></a-torus>
      <a-torus position="0 0 -10" radius="18" radius-tubular="0.02" color="black" segments-tubular="100" scale="1 1.5 1"></a-torus>
      <a-torus position="0 0 -10" radius="17" radius-tubular="0.02" color="black" segments-tubular="100" scale="1 1.5 1"></a-torus>
      <a-torus position="0 0 -10" radius="16" radius-tubular="0.02" color="black" segments-tubular="100" scale="1 1.5 1"></a-torus>
      <a-torus position="0 0 -10" radius="15" radius-tubular="0.02" color="black" segments-tubular="100" scale="1 1.5 1"></a-torus>
      <a-torus position="0 0 -10" radius="14" radius-tubular="0.02" color="black" segments-tubular="100" scale="1 1.5 1"></a-torus>

      <!-- A basic oval circle in the center for the 'scanner' -->
      <a-circle position="0 0 -10" color="red" radius="14" scale="1 1.5 1"></a-circle>
      <!-- wasd control -->
      <a-entity camera look-controls wasd-controls="acceleration:100" position="1 1 60"></a-entity>
    </a-scene>


```
When I first made this I had the oval shape be a circle, but it didn't feel realistic so I changed the shape to be an oval. 

_Then I remade my robot from my previous blog, and I added a sky and made it look better._
```html
<html>
  <head>
    <script src="https://aframe.io/releases/1.7.1/aframe.min.js"></script>
  </head>
  <body>
   <a-scene>
  <a-cylinder position="0 1 6" radius="0.5" height="1.5" color="#FFC65D"></a-cylinder>
  <a-box position="0 2 6" rotation="0 45 0" color="#4CC3D9"></a-box>
  <a-sphere position="0 2.75 6" radius="0.5" color="#EF2D5E"></a-sphere>
  <a-plane position="0 0 6" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane>
  <a-sky color="#ECECEC"></a-sky>
     <a-entity camera look-controls wasd-controls="acceleration:100" position="0 2 11 "></a-entity>
     <a-plane position="0 0 -5" rotation="-90 -2 0" width="50" height="50" color="green"></a-plane>
      <a-sky color="lightblue"></a-sky>
</a-scene>
  </body>
</html>

```

_Teleportation device:_
``` html
  <a-scene>
      <a-sky color="lightblue"></a-sky>
<!-- ground -->
<a-plane position="0 0 -5" rotation="-90 0 0" width="50" height="50" color="green"></a-plane>
<!-- sun -->
<a-sphere position="0 25 -50" radius="5" material="color: yellow"></a-sphere>
<!-- base of house-->
<a-box position="5 2 -10" width="6" height="4" depth="6" color="#70444A"></a-box>
<!-- roof of house -->
<a-cone position="5 5.4 -10" radius-bottom="4" height="3" color="#B3505D"></a-cone>
<!-- Door -->
<a-box position="5 1 -7" width="1" height="2" depth="0.1" color="saddlebrown"></a-box>
<!-- Windows -->
<a-box position="3 2 -7" width="1.2" height="1.2" depth="0.1" color="#C3D4D0"></a-box>
<a-box position="7 2 -7" width="1.2" height="1.2" depth="0.1" color="#C3D4D0"></a-box>
<a-box position="4.6 1 -7" width="0.1" height="0.1" depth="0.1" color="white"></a-box>
<a-camera position="0 1.6 5"></a-camera>
<a-sky color="#E0E0E0"></a-sky>
  <a-box position="-4 1 -5" width="2" height="2" depth="4" color="#8D6E63"></a-box>
  <a-box position="-4 1 -5" width="1" height="1.5" depth="5" color="#F44336"></a-box>
  <a-box position="-4 1 -5" width="1" height="1.5" depth="5" color="#F44336"></a-box>

```

For my future technology I had an idea for a teleportation device, so I made one. I reused my code for the house I had and added the teleporting device next to it. 


### Skills
Some of the skills I've gained are better note-taking skills, and being more creative. I became more creative by trying new ideas and making different models, like houses, robots, and teleportation devices. I've gotten better on doing it myself and not relying on someone to help me or tell me how to do it, or what part to learn. Since we pretty much learned the tool all by ourselves, I had to know myself what is needed for me to learn and what i'm going to use. I've also learned how to take better notes, when I didn't know how to align the shapes I went back to my notes and it helped me a lot, especially when the positions had to be negative or positive. It was confusing at first but then I understood. I was also paying attention to detail by making everything was in the right place, like windows on the house or making the teleportation device be near the house but not too close to the house. Before I started building, I thought about what I wanted to make and how to put everything together.






[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
