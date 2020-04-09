# Covid 19 Face Shield/Visor For Stackable 3D Printing On Single Nozzle Printer

This is my version of the shield from [3dverkstan.se](https://3dverkstan.se/protective-visor/) that stacks well on my single nozzle 3D printer (Creality CR205) using PLA. I am very new to 3D printing and there is a *lot* of information out there, but this is what works for me. Mainly I didn't realise that you literally left a small gap between the rows and that space is what causes the weak link between rows that allows you to snap the visors apart without haveing to clean up a load of support material.

**If you just want the STL files, download this repo and save the file. Currently there's only a 2 stack version, but I intend to add more to the repo going forward**

![Image of Visor](https://github.com/gomako/covid-19-face-shield/blob/master/images/visor.png)

At the time of writing, there is a stacked version for dual nozzle 3d printers, but not for single nozzle. So I made this version for stacking on a single nozzle. 

Currently it's the Europe ISO838 version, which I can make here in the UK using a normal, everyday hole punch.

I followed pretty much everything in this [video](https://www.youtube.com/watch?v=3pK8DqJyOPU) but it took some fiddling about.

## How To Print (well, how I print it, anyway)

 - Open the STL in Ultimaker
 - Layer height is 2.8mm
 - 10% infill
 - No support
 - Add adhesion layer (you may not need this, but I do)

Let it cool down before attempting to separate the layers. There's a thin chamfer at the bottom of each layer where you can wedge a stanley blade in to prise them apart. It might not seem like it will come apart, but once it starts coming apart it's pretty easy.

## How I Made The STL file

 - Downloaded the files from 3D Verkstan, took the ISO838 versions (solid visor, and 1mm thick visor to save material on the final print)
 - Open the solid visor STL file in Fusion 360
 - Turn off Capture Design History by right clicking on the top node of the tree (this is so you can do the following step)
 - Right click the mesh and select `Mesh to BRep`
 - Move/Copy the mesh and translate it up 5.35mm. 
 - Repeat for as many times as you want. I would suggest starting with two so you can see what works, then work up.
 - This is optional, but for the final layer use the 1mm thick visor, as it saves some time as it's not needed to support the layer above

## My Background

I got given a 3D printer on indefinite loan by a generous friend and aside from messing about making silly stuff I haven't really used it as I didn't really have time to spend working out how to use it. I find now that I have lots of time to spare and I really want to do something useful. Staff at my local high school is working hard producing laser cut visors and are distributing them locally to front line staff.

I know what I am making is not ideal, as it's not PETG and it's not as robust as the PRUSA one, but I can make many more per day and my friends that work in the NHS tell me they are needed. They can be sterilized in alcohol or just washed in soapy water and rinsed to be cleaned. PLA is not suitable to be heated.

My printer:

 - Creatlity CR20
 - 0.4mm nozzle
 - PLA
