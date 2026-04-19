# Tool Learning Log

## Tool: **A-frame**

---

### 3/16/26:
* I went to the freedom project tool lists, and clicked on the different links
##### A-frame website
* The guide explains what A-frame is and how to use it.
    * I noticed the A-frame I am on is "old 1.5.0 version" and there is a link for the newer version. The starter code is both the same, the only difference is in the script tag one is 1.5.0 and the other is 1.7.0.
    * https://aframe.io/docs/1.5.0/introduction/
    * https://aframe.io/docs/1.7.0/introduction/
* I was reading the introduction documentation when there was a lot of words I didn't understand.
    * In the components section there are geometries, materials, lights, animations, models, raycasters, shadows, positional audio, and text components that can be used.
##### Videos
* I watched the 1.1 Introduction to Vr video, and after watching it I realized when I was tinkering with A-frame It was doing the same thing.
    * The person making the video copied and pasted the starter code into html, previewed the code, and saw the different shapes.

##### Workshop section
* I went to the google slides called "Aframe MfA22 Escaping Reality", and it had a lot of good information especially on how to make the object look good and realistic.

##### A-frame GitHub
* This is the A-frame repository in github. https://github.com/aframevr/aframe/tree/gh-pages?tab=readme-ov-file
    * In the repository I notice there is some cool examples of what you can make using A-frame.
    * There is multiple types of code you can copy and paste to build VR and AR scenes.

### 3/23/26:
* A-frame can be used to create prototypes of tools, gadgets, and designs.
* You can change the position of shapes.
* I decided to watch some more videos and take notes on it.
##### Videos
#### AFrame Lesson 1.3: Color and material attribute. Sky and plane component.
* `<a-sky color= "blue"></a-sky>` will change the color of the background/sky into blue.
* `<a-plane color= "brown"></a-plane>` if you only type this the ground will not be visible unless you zoom out because there is no coordinates, and the component is default rotated, so you need to add coordinates.
     * This is the code for making the ground. `<a-plane color= "brown" position= " _ _ _" width= "__" height= "__" rotation= "_ _ _ "></a-plane>`
 * You can use images for the sky, but it has to wrap fully around 360 degrees otherwise there will be a distinctive line where they both connect.
 * When making the ground you can also use pictures, but you may have to use more than one. Such as adding "repeat" in your code, so the one picture you picked won't be blurry trying to take up the whole space.
     * You can add pictures of a brick pattern, and if you want it to be smaller you can increase the number with the repeated pictures.
 * You can even add patterns and color on the objects.

#### AFrame Lesson 1.2: Position, rotation and dimension attributes.

##### Rotations
* x-rotation is the object tilting forward or backward along the horizontal axis
* y-rotation is the object spinning left or right along the vertical axis.
* z-rotation is the object twisting around its front and back along the depth axis.

##### Positions
* Positive Z brings objects closer, Negative Z moves objects further back.
* Default position for an object is (0, 0, 0)


##### Dimensions
* Width, Height, Radius
* box has width, height, depth and a sphere has radius
* If you change the radius of a sphere, it will grow in size.
##### Attributes
* When you add an object without defining attributes, it uses default settings.
    * Position: (0, 0, 0)
    * Rotation: (0, 0, 0)
    * Dimensions: (1, 1, 1)
* Objects can overlap if their dimensions bring them into the same space.
    * For example a sphere with a radius of 3.25 might overlap with a box or cylinder if they’re positioned close.

### 3/30/26
* I opened up Jsbin and pasted in the starter code, and I was going through A-frame and its different components.
    * Some of them didn't really do anything but I think its because I didn't do it correct, so I pasted the code into the `<a-scene> </a-scene>`
* One thing that stood out to me was the wasd-controls, when I pasted in the code at first I was moving my mouse. But then when I reread the information part more correctly it said "wasd controls". So I clicked the buttons and was amazed on how it was zooming in and out.
    * `<a-entity camera look-controls wasd-controls="acceleration:100" position="0 1.6 0"></a-entity>` this is the code to paste in. You can change the position on where it stands.

* This is also related to the wasd controls, it is called vive-focus-controls.
    * `<a-entity vive-focus-controls></a-entity>`

    * `<a-entity vive-focus-controls="hand: left"></a-entity>  <a-entity vive-focus-controls="hand: right"></a-entity>`
* Different shapes to add in the scene.
    * https://aframe.io/docs/1.5.0/components/geometry.html#triangle
* hex code colors, https://htmlcolorcodes.com/
* Made a house using geometry shapes.
    `<a-scene>
     <!-- sky -->
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
    </a-scene>
* Making the house wasn't that difficult but I had to make the windows be aligned, put the door in the center. For the handle I copied and pasted the code for my windows, all I did was make the width and height smaller and make it align with the door.

### 4/15/26
Day 1: Watch more videos to learn more information about the tool, and how I can use it to make my future technology look better. I will watch 1.4 because it will show how to actually build the model, and take notes of what I will use.

Day 2: I will pick one of my future technologies I have in my blog and make a couple sketches of what I want it to look like, then I'll make it a little more detailed and then get started on it.

Day 3: I will continue to make  the model  that I want to create.  I can do that by using different shapes, and code from the a frame website so that it can look good.

* The order of components in code doesn't affect the position of the object.
* Example: Building a snowman with three spheres of different sizes and positions:
    * Largest sphere at the bottom (radius larger, position lower).
    * Medium sphere in the middle.
    * Smallest sphere at the top.
* `<a-entity>` acts as a container. like a `<div>`
    * You can use that to make multiple identical model and change the positions.
* `<a-entity position="x y z" rotation="rx ry rz"><!-- complex object components --></a-entity><!-- Copy with different position and rotation --><a-entity position="x2 y2 z2" rotation="rx2 ry2 rz2"><!-- same object components or different --></a-entity>`

* When I was picking one of my future technologies to make the model of, I chose to do the Finger scanning Medical Records.
* Finger scanning Medical Records
    * I made a big circle and added oulines of smaller circles inside of it to look like a finger print.
    * Link for code to finger scanning machine, technology. https://docs.google.com/document/d/1EK4zlr60oSqUgn56KHXMlbDX5XI4W-slK77Qhu47aBc/edit?tab=t.0
    * I made the model of what it will roughly look like, but I might change the shape of the circle to be a oval so its more realistic.

* The finger scanning I changed the shape from a cirle to be an oval.
    * https://docs.google.com/document/d/1orSj0rE4QBBxhv2GhoVhi5-SH8g5HVj-55JhgJeeXbA/edit?tab=t.0

* I made the model of my robot again. In try 1 its just the robot but try 2 is with a sky and background.
    * https://docs.google.com/document/d/12Xmsy1UiolkizXlUbU9kOL8LeXsZ6yim-FVzWQ4XNUQ/edit?tab=t.0

* Now I made the teleportation device.
    * https://docs.google.com/document/d/1yyJBjTm3WnLY-VKRO6XZOexINkYZcMQA02Mb7VDdpR0/edit?tab=t.0#heading=h.n30f2ck5cvau

    * While making the device I reused the code I made for the house and I just added a rectangle box and red doors.
* Out of the future technologies I made models of I don't know which one am I going to use for my project because I'm proud of all of them, and how they turned out.





<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
