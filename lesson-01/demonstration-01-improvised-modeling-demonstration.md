![](/assets/A_1.jpg)

This is what the blender main screen looks like when you first open it up

![](/assets/A_2.jpg)

If you go to the top of the screen you'll see that there is a menu called File

![](/assets/A_3.jpg)

click on user preferences

![](/assets/A_4 .jpg)

if you are working on a laptopn that does not have a dedicated number pad then select emulate numpad from within the Input Tab

![](/assets/A_5.jpg)

by default the program presents a cube within what is called object mode

![](/assets/A_6.jpg)

Use the indicated drop menu or the tab button to go between object and edit modes

![](/assets/A_7.jpg)
you can use the scrollwheel to zoom in and out

![](/assets/A_8.jpg)

you can use Z button to toggle in and out of wireframe and bounding box modes or use the indicated sub menu

![](/assets/A_9.jpg)

if you push down on the scroll wheel or otherwise known as middle mouse button and drag you can change your orientation or what is also known as orbit

![](/assets/A_10.jpg)

if you press the number keys you will see that they change your perspective to specific views such as top left bottom right front and back

![](/assets/A_11.jpg)

pressing the number five will toggle between two point perspective and orthoganal views more on this later

![](/assets/A_12.jpg)

you can stretch or expand menus and windos by dragging on their dividers

![](/assets/A_13.jpg)
Here you can see that I have expanded the function menu on the left and the modifier and layer menus on the right

![](/assets/A_14.jpg)

you can click and drag out additional windows by clicking on and dragging from the lines in the corners

![](/assets/A_15.jpg)

you can change each partitioned window into a different and specific view type

![](/assets/A_16.jpg)

you can also set up a screen to view from a camera for the purpose of rendering specific angles

![](/assets/A_17.jpg)

by holding down the shift and middle mouse button you can pan your view

![](/assets/A_18.jpg)

by click on the lines in the corner of any view window you can drag it over other windows to collapse them

![](/assets/A_19.jpg)

Expand the modifier menu on the right

![](/assets/A_20.jpg)

If you click on the wrench tab and then on add modifier you can find a list of potential modifiers to chose from

![](/assets/A_21.jpg)

it's important that you familiarize yourself with the various orbiting and panning methods

![](/assets/A_22.jpg)

here we have an example of the default cube in wireframe mode which makes it easier to see through it

![](/assets/A_23.jpg)

these three icons allow you to choose between vertex line and face selection modes

![](/assets/A_24.jpg)

under face mode you can right click on the black squares to select the corresponding faces

![](/assets/A_25.jpg)
if you continue holding the shift button and selecting faces you can select several at a time

![](/assets/A_26.jpg)

you can then perform operations to multiple faces at once, such as extruding them

![](/assets/A_27.jpg)

observer the different behavior between extrude region and extrude individual

![](/assets/A_28.jpg)

pressing "A" will deselect the already selected faces

![](/assets/A_29.jpg)

pressing "A" another additional time will select all faces

![](/assets/A_30a.jpg) 

you can also subdivide the Faces 

![](/assets/A_30.jpg)

subdividing will help you take control over forming your object in finer detail

![](/assets/A_31.jpg)

The line Selection mode lets you take control of your object using line manipulation

![](/assets/A_32.jpg)

vertex mode allows you to select individual vertices

![](/assets/A_33 .jpg)

wireframe makes it much easier to see sometimes, especially when selecting parts of the object behind the immediate faces

![](/assets/A_34.jpg) 

here I use the shrink or fatten function to narrow the gap

![](/assets/A_35.jpg)

after pressing Z to see the frames my object is starting to look like some kind of crystal or ore

![](/assets/A_36.jpg)

If we then audition the image with the subdivision modifier, we can see that it curves a bit more- almost looking like a cashew or peanut

![](/assets/A_37.jpg)

selecting vertices the c-circle or b-marqui selection tools with the wireframe mode makes it easier to quickly grab entire regions

![](/assets/A_38 .jpg)

with the r-rotate tool you can constrain to specific axis by typing an additional x y or z and then moving your mouse or typing a specific angle

![](/assets/A_39.jpg)

next I will return to bounding box mode and remove the subdivision modifier

![](/assets/A_40.jpg)
next I select some vertices, press X to delete, them and then specify that I want to delete vertices

![](/assets/A_41.jpg)

blender prefers to use faces of 4 sides so I select sets of 4 immediately neighboring pairs and press F join them as faces

![](/assets/A_42.jpg)

next I press ctrl with alt or option and q to enter quad view mode

![](/assets/A_43.jpg)

next I use the border select tool by pressing b and I try to make clean edges of vertices

![](/assets/A_44.jpg)

eventually the form becomes boxier

![](/assets/A_45.jpg)

select an edge and press loop cut and slide b

![](/assets/A_46.jpg)

loop cut and slide is similar to the subdivision function and modifier but allows for certain flexibilities

![](/assets/A_47.jpg)

I select and evenly stagger of points

![](/assets/A_48.jpg)

This is what it could look like with some scaling and subdivision

![](/assets/A_49.jpg)

once you increase the number of subdivisions you can see that the shape goes from colder mechanical and edgy into a more curvy soft and organic form

![](/assets/A_50.jpg)

but that's getting ahead of ourselves- what we want is more about proportion at this stage so let's revert to non-subdivision

![](/assets/A_51.jpg)

it's always good to save in incremental states- here I revert to an earlier version when we were working with this peanut looking thing

![](/assets/A_52.jpg)

I select the whole thing using the "A" key

![](/assets/A_53.jpg) 

by pressing g for scale and then z to constrain deformation to one dimension I am able to flatten the peanut into a something more like a biscuit

![](/assets/A_54.jpg)

if you zoom out it almost looks like the beginning of the form for a seahorse

![](/assets/A_55a.jpg)

Here we press g to scale and y to constrain deformation to the Y axis

![](/assets/A_55b.jpg)

here we use the same method but choose to compress it by giving negative values for Y

![](/assets/A_56.jpg)

Here we press r to rotate the shape and again we can use constrain to dimension- also you can override the manually rotated measurement by typing in a specific value- this also work for scaling

![](/assets/A_57.jpg)

at this point we are just playing around with features- improvising- trying to treat this all like clay- so let's rotate this clump and mirror it

![](/assets/A_58.jpg)

and like clay let's select mirror on the Y axis and smash them into each other

![](/assets/A_59.jpg)

at this point in time you can simply push and pull them apart and there is no deformation- because the mirroring has not been applied

![](/assets/A_60.jpg)

however once clipping is applied vertices will terminate their location whenever they come upon the origin points of reflection

![](/assets/A_61.jpg)

I don't know about you but I think this sort of looks like a cartoon cat so let's go with it

![](/assets/A_62.jpg)

if you look at this in wireframe mode you can see that there's some unwanted geometry inside of the mesh

![](/assets/A_63.jpg)

let's upon up the hood by deleting a face and take a look inside

![](/assets/A_64.jpg)
after selecting and deleting the vertices I select the exterior three vertices and press F to make Triangular face where the gap was

![](/assets/A_65.jpg)

let's see if we can expand on my cat theory

![](/assets/A_66.jpg)

let's select this middle side of the face and enable the indicated proportional editing mode using the default settings

![](/assets/A_67.jpg)

let's leave proportional editing on and deform the mesh a bit

![](/assets/A_68.jpg)

this is starting to look more cat like

![](/assets/A_69.jpg)

a little more cat like

![](/assets/A_70.jpg)

I will now go to the select tab and select edge loops

![](/assets/A_71.jpg)

now I will click on the red arrow and drag this portion of the mesh inwards

![](/assets/A_72.jpg)

I want to rework the back so I select face from face mode and begin deleting

![](/assets/A_73.jpg)

in order to keep all the faces at 4 sides I reinsert an interior segment at the point of reflection and press w for a submenu- and select subdivide- now this face can be rebuilt with four points

![](/assets/A_74.jpg)

next I will select the front-most edge loop and drag the red portion of the 3D cursor to extend the face outwards

![](/assets/A_75.jpg)

the ears will need some tweaking

![](/assets/A_76.jpg)

let's audition this under the subdivision modifier to get a clearer sense of where our geometry does and does not work

![](/assets/A_77.jpg)

those eyes are really not defined- lets delete the modifier and continue

![](/assets/A_78.jpg)

Here I create additional edge-loops for increased definition

![](/assets/A_79.jpg)

Here I reenable proportional editing and pull from the mesh with the sphere setting to create googly eyes

![](/assets/A_80.jpg)

I decide to push the faces in the opposite direction to create eye cavities

![](/assets/A_81.jpg)

After some cleaning up this is starting to look even more like a cat face

![](/assets/A_82.jpg)

Here I auditioned the face in Quad view mode under a subdivision modifier to get a sense of where this could go if I were to have continued

