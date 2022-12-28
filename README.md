# Virtual-Reality---CS-4331---Project-1

**Play it here**: 
https://lavender-tame-tote.glitch.me/


In order to make this scene in Aframe, I first watched Danilo Pasquariello's amazing tutorial playlist on youtube: 
https://www.youtube.com/watch?v=ktjMCanKNLk&list=PL8MkBHej75fJD-HveDzm4xKrciC5VfYuV

Shortly after I began my work by creating a chair, by flatening one square, duplicating and rotating it, then making four stands each 1 space away from each 
other for simplicity and ease of use. 

![Alt text](https://raw.githubusercontent.com/SaifTTU/Virtual-Reality---CS-4331---Project-1/master/show10.png)

Next I use this same principle to create a desk, I decided to make it have a thinker rectangle underneath to symbolize a drawer cabinet, when my rectangle went 
a little too low at first. So having a grasp on the primitive objects, I wondered if I could create a computer. I used two cylinders, on flat for the base, and one 
long to represent the base. 

I then made two rectangles, one to represent the desktop, and another to represent the monitor. I also made the base using two cylinders, one flat and one long. Later on I found out how to add images by typing in 
src="(source url)" within the brackets, to give it that image of me playing league of legends. 

Next game the ground, the walls, and the ceilings, which are just more objects. 
In order for me to portray the walls realistically, I needed to use the repeat "3 3" command to make the wood on the walls duplicate. I took inspiration from the 
sample file we got and titled it #lightwood. 

I decided I didn't want all my walls to be the same so I made the North side have two smaller narrow boxes of equal height to make room for a window. I then made
long and narrow boxes and rotated them to represent the beams of a window looking out.


This is when I got the idea to use a pool. All I had to do was make another box similar to the way I made the ground and place it on a dpeth of -10 to face out the window.

![Alt text](https://raw.githubusercontent.com/SaifTTU/Virtual-Reality---CS-4331---Project-1/master/show5.png "show4.png")

The lighting for this project came much later. There is a couple of red lights to represent the fire, the sun, the blue pool against the house, theres a few faint
lights for the tv and some corrective lights implemented because the blue of the pool was shinning through the window.

I made glass boxes by setting the opacity of the material to .1 for the windows.

![Alt text](https://raw.githubusercontent.com/SaifTTU/Virtual-Reality---CS-4331---Project-1/master/show9.png)

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


![Alt text](https://raw.githubusercontent.com/SaifTTU/Virtual-Reality---CS-4331---Project-1/master/show4.png)

Next up was the animating, 
https://www.youtube.com/watch?v=p3mNNZ356Ko
I used the most basic principle in this tutorial video to help me create a rotating fan, the fan includes 4 blades slightly curved like a real fan, they rorate about a flat cylinder and have another two cylinders, on that represents the part the blades are connected to, and another that connects them to the ceiling. 

![Alt text](https://raw.githubusercontent.com/SaifTTU/Virtual-Reality---CS-4331---Project-1/master/show7.png "whole room")

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


![Alt text](https://raw.githubusercontent.com/SaifTTU/Virtual-Reality---CS-4331---Project-1/master/show6.png)
![Alt text](https://raw.githubusercontent.com/SaifTTU/Virtual-Reality---CS-4331---Project-1/master/show8.png)
![Alt text](https://raw.githubusercontent.com/SaifTTU/Virtual-Reality---CS-4331---Project-1/master/show11.png)
![Alt text](https://raw.githubusercontent.com/SaifTTU/Virtual-Reality---CS-4331---Project-1/master/show3.png)



I then added teleporation movement using inspiration from this glitch project: 
https://glitch.com/edit/#!/puzzled-pretty-dollar?path=index.html%3A8%3A2
. Studies show that including a teleportaion feature helps to reduce motion sickness when compared to standard locomotion in VR. That is why I chose to include it.

Videos which depict my project: 

https://www.youtube.com/watch?v=NMsRm1Ap2lY

https://www.youtube.com/watch?v=b1iYXouXOOk

List of the Models I created:

1. Chair

2. Table

3. Computer

4. Chimeny

5. Fireplace Glass/ Glass Door Handle (which animates!)

6. Fan

7. Clock (I made and animated those objects with two boxes and two cylinders, only added a clock image afterwards)

8. Bed

9. Shelf.

10. Plant Bed with soild

11. Pool. (thin box)

12. Sun (sphere, with lighting)

13. Rug (thin box)

14. Windows (multiple walls, with perches, beams, translucent windows from the outside)

15. Brick Walls

16. Keyboard (its just a white box, but hey!)

17. Calendars 1 and 2. (I drew them, using paint)

![Alt text](https://raw.githubusercontent.com/SaifTTU/Virtual-Reality---CS-4331---Project-1/master/calendar.jpg "calendar")

18. Webs (I drew this image in photoshop)

![Alt text](https://raw.githubusercontent.com/SaifTTU/Virtual-Reality---CS-4331---Project-1/master/webs.png "webs")

Links to the Images I used: 

1. lightwood: https://www.homedepot.com/p/Orchard-Light-Grey-Wood-Panel-Vinyl-Peelable-Roll-Covers-56-sq-ft-414-56909/204206734

2. blankets (title: bedsheets): https://www.freepik.com/free-photo/colorful-bed-sheet-texture_6345746.htm

3. computer screen: https://www.google.com/search?q=victory+league+screen&tbm=isch&sxsrf=ALeKk00ou5galRiMlSRYL36ZiTxX3BNBNw:1601421078318&source=lnms&sa=X&ved=0ahUKEwj104i0vo_sAhUIcq0KHbO_CJ8Q_AUI6wQoAQ&biw=1077&bih=787#imgrc=GU7VCwGwygUG8M

4. pool: https://lh3.googleusercontent.com/proxy/nJK32ogmuf2ptRVA3uDnU6yy8cTz7DEW94zVR_Olv3j84yY6uGKrkPP9AtKXsBC_WC7REfq8Gi0l9v-VGyuTVIKlqxHxfEgs_Bjq91zpPW48jRMr615MPWVaDGcJ5EL3hP0e5Ppb7lrz5RQug0wAcXsyYwrE

5. soil: https://www.pinterest.com/pin/572027590170631712/?nic_v2=1a3VNccUC

6. rug: https://www.fostersfurniture.com/area-rug-texture-confetti-ch20800-midnight-colorway

7. bricks: https://www.123rf.com/photo_87160211_seamless-brick-wall-texture.html

8. clock: https://www.deviantart.com/agf81/art/Clock-Face-2-169291889

9. hologram: (I cropped out part of this image to create the hologram) https://www.pinterest.com/pin/58828338865930590/?nic_v2=1a3VNccUC

10. leia: https://www.pngguru.com/free-transparent-background-png-clipart-raeay

11. Social Distancing Sign: https://www.seton.com/be-mindful-of-social-distancing-sign-bk0322.html?utm_campaign=PC-01-Safety%26FacilitySigns_SocialDistancingSignsCOVID19_Seton_PLA_NB_C_Google_US&utm_source=google&utm_medium=cpc&utm_term=&matchtype=&device=c&adgroupid=Social+Distancing+Signs&keycode=WS0282&gclid=CjwKCAjw2dD7BRASEiwAWCtCbzAEAsZEkHSlcJk9CP-ITifV4AUxf9F_8nJOhtaIQXkmn6pzjVeVXRoC_5kQAvD_BwE&gclsrc=aw.ds

12. Mask Required Sign: https://mn.gov/covid19/media/share-message/for-businesses/index.jsp

13. Wear A Mask Sign: https://stratospheredesigns.com/posts/free-printable-face-mask-safety-signs-in-8-colors/

14. Floor decal: https://www.seton.com/floor-safety-signs-stay-6-feet-apart-blue-me1116.html?utm_campaign=PC-01-FacilitySigns_CatchAllTest_Seton_PLA_NB_C_Google_US&utm_source=google&utm_medium=cpc&utm_term=&matchtype=&device=c&adgroupid=Catchall&keycode=WS0282&gclid=CjwKCAjw2dD7BRASEiwAWCtCbyURPD_FgdS3WnEwKANRPsEKRie0Hvt75oonBf8JmtwgwR2NfNWpWRoCHbQQAvD_BwE&gclsrc=aw.ds

15. 3 Fask Mask Images: https://www.rawpixel.com/search/face?sort=curated&type=png&page=1

Links to the Models I used: 

1. cactus: https://sketchfab.com/3d-models/fishhook-barrel-cactus-plantpointschallenge-1f088de099d24cea9d8bba2a3d067403

2. books: https://sketchfab.com/3d-models/11-books-householdpropschallenge-ea227e0235a54af48ae11142402b4323

3. nintendo switch: https://sketchfab.com/3d-models/nintendo-switch-75c5052910ea46feaad64509d96556fe

4. ps5: https://sketchfab.com/3d-models/ps5-d788de3735964151a3e24fd59c0f1956

5. ps5 controllers: https://sketchfab.com/3d-models/ps5-controller-f75caead1dc1474195eb32a7f4c71117

6. bb8: https://sketchfab.com/3d-models/bb8-5b78c3ca7dbc4f64b5784bb1fb54b540

7. storm trooper helmet: https://sketchfab.com/3d-models/storm-trooper-helmet-1e49d4dd73c746d4b131c58dfe471bd7

8. link: https://sketchfab.com/3d-models/link-from-legend-of-zelda-dcb4cf57af564a00b702f995a9a69f1

9. desktop pc: https://sketchfab.com/search?q=computer+desktop&sort_by=-relevance&type=models

10. mouse: https://sketchfab.com/search?q=mouse+computer&sort_by=-relevance&type=models

11. pillows(printed two of them): https://sketchfab.com/3d-models/pillow-fb3ff27a30bb4243b8006bc997f4d8a4

12. door: https://sketchfab.com/3d-models/lowpoly-door-809e9d0da4f34b819de5668252ead5f0

13. hand sanitizer: https://sketchfab.com/3d-models/sanitizer-bottle-ec67d7141333464ca1061320452f06a2

