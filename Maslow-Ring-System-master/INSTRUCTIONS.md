Because the sled is a shape which could be difficult to make by hand we are going to make a rough version by hand and then use Maslow to cut the final version.

This process is largely the same regardless of which frame design you build, so don't worry if the pictures look a little different than your frame.

### Step 1: Cut plywood parts

If you have not already done so, cut the following shapes from a sheet of plywood. The dimensions of these parts are not critical, and you can cut them by hand.

![](https://raw.githubusercontent.com/MaslowCommunityGarden/Maslow-Ring-System/master/Cutting%20The%20Sled/Plywood%20Cut%20Dimensions.PNG)

### Step 2: Add holes

Next, we need to drill holes in these parts. Adding a hole in the center of the sled will let the router pass through. Adding holes at the bottom of the sled and in the brick holders will let us use bolts to hold the bricks in place.

Using your router, route out an approximately 1.5" by 1.5" hole in the center of the sled. 

Then place the two brick holders in the lower corners of the sled and drill through them using a 1/4 inch drill bit (7mm).

![](https://raw.githubusercontent.com/MaslowCommunityGarden/Maslow-Ring-System/master/Cutting%20The%20Sled/Sled%20with%20holes.jpg)

### Step 3: Attach router

Attach your router to the sled. This step will vary depending on the router you are using so it's a little bit up to you, but the gist will be the same on most routers.

You will probably need to remove the handles from your router to make it fit within the ring. On the Ridgid router, the handles are held on using two bolts hidden under the caps on the handles. Removing the caps over the bolts can be quite difficult, I ended up drilling a hole in one to get access to the bolt.

Remove the router base plate, and attach the router to the sled using the same bolt holes that the base plate used to attach. The bolts which held the base plate may not be long enough to pass through the plywood.

The base of the router can be used as a template to drill holes for the router mounting bolts.

![](https://raw.githubusercontent.com/MaslowCommunityGarden/Maslow-Ring-System/master/Cutting%20The%20Sled/Using%20baseplate%20as%20a%20template%20to%20drill%20holes.jpg)

![](https://raw.githubusercontent.com/MaslowCommunityGarden/Maslow-Ring-System/master/Cutting%20The%20Sled/Router%20attached.jpg)

### Step 4: Attach the ring and bricks

Attach the two bricks using the bolts and nuts provided and the two wooden brick retainers.

![](https://raw.githubusercontent.com/MaslowCommunityGarden/Maslow-Ring-System/master/Cutting%20The%20Sled/Bricks%20attached.jpg)

Attach the ring to the sled. The ring attaches using the three adjustable 'L' brackets, the small wood screws, and the small nuts and bolts shown below.

![](https://raw.githubusercontent.com/MaslowCommunityGarden/Maslow-Ring-System/master/Cutting%20The%20Sled/Ring%20parts.jpg)

![](https://raw.githubusercontent.com/MaslowCommunityGarden/Maslow-Ring-System/master/Cutting%20The%20Sled/Ring%20hardware.jpg)

First, attach the 'L' brackets to the ring using the small nuts and bolts, then attach the ring to the sled using the wood screws such that the ring is concentric around the router. 

![](https://raw.githubusercontent.com/MaslowCommunityGarden/Maslow-Ring-System/master/Cutting%20The%20Sled/Ring%20floating.jpg)

![](https://raw.githubusercontent.com/MaslowCommunityGarden/Maslow-Ring-System/master/Cutting%20The%20Sled/Ring%20bolted%20down.jpg)

For now do your best to make the ring concentric around the router, on the final sled we will use alignment marks to dial the placement in.

Note that the 'L' brackets are designed to let you move the ring up and down to adjust for your router's center of gravity. When supported by the ring the router should hang vertically. You can move the ring in and out to account for your router's weight distribution.

### Step 5: Attach the carriages to the ring

Now we need to assemble and attach the carriages to the ring. To do this we will need the shoulder bolts, bearings, washers, and nuts.

![](https://raw.githubusercontent.com/MaslowCommunityGarden/Maslow-Ring-System/master/Cutting%20The%20Sled/Carriage%20hardware.jpg)

The completed assembly will have the shoulder bolt sandwiching the washers on either side of the bearing. You should be able to tighten the nut down snugly and still have the bearing rotate freely. If the bearing does not rotate freely, check that the shoulder bolt has not become caught on one of the washers.

![](https://raw.githubusercontent.com/MaslowCommunityGarden/Maslow-Ring-System/master/Cutting%20The%20Sled/Close%20up%20of%20carriage%20stack.jpg)

Assemble one carriage on either side of the ring.

![](https://raw.githubusercontent.com/MaslowCommunityGarden/Maslow-Ring-System/master/Cutting%20The%20Sled/Carriages%20on%20ring.jpg)

### Step 6: Attach sled to frame

Next, we are ready to hang the sled on the machine! To attach the sled to the machine pass the free end of each chain through the hole in the end of each carriage and secure it with a cotter pin.

![](https://raw.githubusercontent.com/MaslowCommunityGarden/Maslow-Ring-System/master/Cutting%20The%20Sled/Close%20up%20of%20chain%20attaching.jpg)

![](https://raw.githubusercontent.com/MaslowCommunityGarden/Maslow-Ring-System/master/Cutting%20The%20Sled/Overview%20of%20chain%20attaching.jpg)

### Step 7: Calibrate

Now it's time to calibrate the machine. Because each machine is built by hand a calibration step is needed to precisely measure your machine so that it can cut accurately.

To calibrate the machine launch Ground Control, then click **Action -> Calibrate**

![](https://raw.githubusercontent.com/MaslowCommunityGarden/Maslow-Ring-System/master/Cutting%20The%20Sled/Clicking%20the%20calibrate%20button.PNG)

### Step 8: Generate Gcode

Next, we need to generate the gcode file which Maslow will use to cut the parts. The design files for the sled can be downloaded under the "files" tab on this page. If you already have a preferred piece of software to generate gcode files feel free to use it, if not there are step by step instructions to use the free online MakerCAM program [here](https://github.com/MaslowCNC/Mechanics/wiki/Generating-Gcode-Using-MakerCAM).

A video describing how to use the free online Easel software is available [here](https://vimeo.com/253064466).

![](https://github.com/MaslowCNC/Mechanics/blob/master/Documentation/MakerCAM/gcode%20generated.png)

### Step 9: Cut the final sled

Open the gcode file in Ground Control by clicking **Actions -> Open File** and then pressing the green start button when you are ready to begin cutting.

Keep in mind that you can move the gcode file around on your 4x8 sheet by moving the router to the desired starting point and pressing the "Define Home" button.

![](https://raw.githubusercontent.com/MaslowCommunityGarden/Maslow-Ring-System/master/Cutting%20The%20Sled/Cutting%20the%20sled%20in%20GC.PNG)

### Step 10: Re-attach the hardware

Next, we need to move the hardware from the temporary sled to the newly cut sled. All of the hardware attaches in the same way that it did on the temporary sled.

Note that the final sled has alignment holes to accurately position the ring and that the holes around the bolts for the bricks are countersunk to hide the bolt heads.

Instructions to install the z-axis if you have one can be found [here](https://github.com/MaslowCNC/Mechanics/wiki/How-To-Assemble-The-Z-Axis)

![](https://raw.githubusercontent.com/MaslowCommunityGarden/Maslow-Ring-System/master/Cutting%20The%20Sled/Use%20alignment%20holes%20to%20position%20ring.jpg)

### Step 11: Round over edge

Your sled will slide across the work area much more smoothly with a rounded edge. This can be done using either a round-over bit or some sandpaper.

When your sled is finished re-attach it to the machine and you are ready to start making things!

Note: A quick sanding of the inside edge of the ring can smooth out the protective coating over the metal and help the bearings to move more smoothly
