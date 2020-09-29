# Virtual-Reality---CS-4331---Project-1

https://lavender-tame-tote.glitch.me/

Links to the Images I used: 

Links to the Models I used:

In the process of making this scene I first encountered Danilo Pasquariello's amazing tutorial playlist on youtube: 
https://www.youtube.com/watch?v=ktjMCanKNLk&list=PL8MkBHej75fJD-HveDzm4xKrciC5VfYuV

Shortly after I began my work by creating a chair, by flatening one square, duplicating and rotating it, then making four stands each 1 space away from each 
other for simplicity and ease of use. 


Next I use this same principle to create a desk, I decided to make it have a thinker rectangle underneath to symbolize a drawer cabinet, when my rectangle went 
a little too low at first. So having a grasp on the primitive objects, I wondered if I could create a computer. I used two cylinders, on flat for the base, and one 
long to represent the base. 

I then made two rectangles, one to represent the desktop, and another to represent the monitor. Later on I found out how to add images by typing in 
src="(source url)" within the brackets, to give it that image of me playing league of legends. 

Next game the ground, the walls, and the ceilings, which are just more objects. 
In order for me to portray the walls realistically, I needed to use the repeat "3 3" command to make the wood on the walls duplicate. I took inspiration from the 
sample file we got and titled it #lightwood. 

I decided I didn't want all my walls to be the same so I made the North side have two smaller narrow boxes of equal height to make room for a window. I then made
long and narrow boxes and rotated them to represent the beams of a window looking out.

This is when I got the idea to use a pool. All I had to do was make another box similar to the way I made the ground and place it on a dpeth of -10 to face out the window.

The lighting for this project came much later. There is a couple of red lights to represent the fire, the sun, the blue pool against the house, theres a few faint
lights for the tv and some corrective lights implemented because the blue of the pool was shinning through the window.

I made glass boxes by setting the opacity of the material to .1 for the windows.

Now that I had a box house, I decided the outside didn't look realistic enough. So I decided to implement a similarly shaped outside layer of boxes that I just
changed the texture and repeat too for the bricks.

A similar method was utilized for implementing my shelf, each rectangular base is equally distant from the next, the sides are simply rotated 90 degrees in the
y direction to simulate a real wooden shelf, which I later would add books and other small models too. 

This same process was how I made the bed, I made one long backboard, and a smaller backboard. I got inspiration to do this when I accidentally made one shelf side 
too small and decided I liked the way it looks. So then I made a base that connected the two. I duplicated this and made a slighly smaller, but thicker square to 
serve as the mattress. I duplicated it again and decreased the depth but made the height and width ever so slighty larger and colored it blue to resemble the 
blanket on top of a mattress. Much later when I found out how to add 3D models, I added pillows.

As for 3D Models, my process came from the help of these two videos: 
For uploading textures onto primitive objects: 
https://www.youtube.com/watch?time_continue=5&v=klnwT3vGCPw&feature=emb_logo
For simplifying the way your import your 3D models:
https://learn.framevr.io/project1/part3

Using this I was both able to add materials onto objects, but I'd also discovered a way to include gltf models in my assets using urls from github like I do with 
my texture images. 
I scoured sketchfab for all the best models. I made a list of every model I wanted to include and made sure they were low poly enough to run in AFrame before 
downloading.
One thing I wanted to include was trash, webs and stuff that the user could get rid of by clicking on them, to represent covid/non-covid more. I ended up settling
on webs to create this effect way later.
I drew those webs, because online images were not coming out transparent like I wanted them to. On the positve side these are really low resolution and
thus take up way less space.
Additionally I drew up a Calendar of March denoting the time when COVID started for me and all my plans were changed. This symbolizes all of the many plans I had 
suddenly getting cancelled. Once I found out how to animate opacity and such, I made this fade into the original calendar I drew using two separate images, one
directly behind the other to create this illusion. 

Next up was the animating, 
https://www.youtube.com/watch?v=p3mNNZ356Ko
I used the most basic principle in this tutorial video to help me create a rotating fan, the fan includes 4 blades slightly curved like a real fan, they rorate about
a flat cylinder and have another two cylinders, on that represents the part the blades are connected to, and another that connects them to the ceiling. 

I used this same principle, but edited the sides to create a clock. I then manipulated the dur (duraction) of the animtion to 1/12 of the minute hand for the hour
hand. I them rotated this object in place and gave it the clock texture I found online, and placed it directly above my shelf.

I started thinking about making fire cubes like the ones I see in the Oculus Quest home, so I created 6 yellow square objects that rise up and different intervals
to create this fire like affect. Lighting is used to sell the sense of heat to the user. 

Next up came filling the shelves. I decided on using low poly models. Essentally every model you use in AFrame needs to be scaled in some way, typically needing to 
be scaled way down, so low poly models fit this requirement the best. I added Link, and a storm trooper helment but it was looking a bit empty so I decided to add
books. At first I added one book at a time and rotated and flipped them ever so incrementally. Then I decided on using a little bit larger models, I end up using
3 different types of models for books, and a total of 15 models to sell the variety. 

A very similar process was utilized when I added the TV, the PS5 (the controllers took a little bit of time rotating), the BB8 Droid.

Additionally, the plant by the side of the window came to me from this vidoe I watched about redocorating the house, I had orignally put a green brush colored 
scqure in place of actual planets. Later i changed this brush color to soil color and added the Cactus plant 3D model in its place. It is a very low poly model but
it looks great which is why I used it.

It was finally time to implement the covid 19 tweaks. I first got some practice by making my chimney glass animatable on click. The process of making this was similar
to the way I made the table, only now it was being informed by all the lessons I had previously learned, like how to make a transparent object, how to make them
all connected to one another, how to properly space everything for the door handle. 

So how it was time to animate the webs. I had orignally placed allot of webs in the room and it looked very halloween themed. I had realized that the player would
nned to reach these locations and it didn't make sense to include them all of the walls and ceilings like I had did. 
I orignally just made the animation property="material: opacity" and set "to: 0" but later went in and made these webs go down as if they were disolving and falling
to the floor.
The calendar was a much easier feat to accomplish since I had already created a seperate image for the cleaned calendar. 
Pillows were the last image I had added to the room. 
