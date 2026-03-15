# Entry 4: My Tool
##### 3/14/26

For my freedom project, the tool I chose is **_A-frame_**. We had to pick out 3 tools we wanted to use, I picked A-frame, Get-foundation, and Sass. We were tinkering with ours tools so we could pick one to use for the rest of our freedom project. So before I started tinkering with my tool, I was looking at all the things that were on the website. The A-frame website had a FAQ's part and I was just reading the questions most people had, and the answers/solutions. For the get-foundation website I was pretty confused on where to click, but when I pressed get started, and then clicked the html templates. There was alot to choose from, I picked the News or Magazine template and downloaded it. It showed me the html code. I copied and pasted it into Jsbin and just started tinkering, like changing up the content. But I chose A-frame as my final tool because I can use it to make a robot, or 3D organs.

#### Robot
This is the code I was tinkering with and changing up for A-frame. I wanted to make the shapes stack on top of each other to make a robot looking shape. It was a bit challenging because everything had to be straight, and the shapes needed to align with each other. The first time I tried it there was spaces inbetween the shapes, it was floating ontop of each other and it didn't really look good. But I changed the numbers to be smaller and not that far from each other. 
```
<a-scene>
  <a-cylinder position="0 1 6" radius="0.5" height="1.5" color="#FFC65D"></a-cylinder>
  <a-box position="0 2 6" rotation="0 45 0" color="#4CC3D9"></a-box>
  <a-sphere position="0 2.75 6" radius="0.5" color="#EF2D5E"></a-sphere>
  <a-plane position="0 0 6" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane>
  <a-sky color="#ECECEC"></a-sky>
</a-scene>
```

#### Teleporation 
This is the code I was using for my teleportation. I made it so there is a big box, to be used as the thing you go inside when you want to teleport. There is 2 red doors in the front, so you go in from there. A challenge I had while making this was, when I first changed up the code I couldn't see the red doors. So I was experiementing by increasing the height by alot so I could see where it was, and I saw that the doors was behind the box and not in the front. I changed the positions of the doors and the box. I made the first and last number be the same for all but the middle number for the box is a 2, and the doors a 1.80 so it will be infront of the box. I also made the height and the width smaller because it will look more of a door and not blend in with the box. 
```
<a-scene>
  <a-sky color="#E0E0E0"></a-sky>
  <a-box position="0 2 6" width="2" height="2" depth="4" color="#8D6E63"></a-box>
  <a-box position="0 1.80 6" width="1" height="1.5" depth="5" color="#F44336"></a-box>
  <a-box position="0 1.80 6" width="1" height="1.5" depth="5" color="#F44336"></a-box>
</a-scene>
```


### Sources:
For the sources I mostly just used [A-frame.](https://aframe.io/) for tinkering and used [Jsbin.](https://jsbin.com/?html,output) to preview and see how it looks like. Before adding, and commiting it to my ide. 


### Skills:
Some skills I’ve learned how to work with 3D design tools, think creatively, and to just try it out because you have nothing to lose. I also got better in researching things in general, because I used to just find something and use the first one that popped up. But now I looked for multiple different resources, and fully dive into where I'm researching and find my inforamtion. Another skill is being able to adapt easiler to certain things. For using A-frame in the begining I was very confused but I researched and watched videos on where/how to start using A-frame. 


[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
