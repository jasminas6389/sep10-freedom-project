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
* Rotations
    * x-rotation is the object tilting forward or backward along the horizontal axis
    * y-rotation is the object spinning left or right along the vertical axis.
    * z-rotation is the object twisting around its front and back along the depth axis.
* Positions
    * Positive Z brings objects closer, Negative Z moves objects further back.
    * Default position for an object is (0, 0, 0)
* Dimensions
    * Width, Height, Radius
    * box has width, height, depth and a sphere has radius
    * If you change the radius of a sphere, it will grow in size.
* Attributes
    * When you add an object without defining attributes, it uses default settings.
        * Position: (0, 0, 0)
        * Rotation: (0, 0, 0)
        * Dimensions: (1, 1, 1)
* Objects can overlap if their dimensions bring them into the same space.
    * For example a sphere with a radius of 3.25 might overlap with a box or cylinder if they’re positioned close.




<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
