# Watercolour_Pen_Plotter
(WIP)


## About:
The Watercolour Pen Plotter is a CNC machine designed to operate like a traditional pen plotter but tailored for watercolor painting on traditional 8.5 x 11 paper. The goal is to create a compact, user-friendly frame with an added feature for mixing paint. The CNC machine will paint freely, blending colors and adjusting shades by varying the paint-to-water ratios through an automated process.

## Progress:

Summary: 
_________________________________________________________________________________________________________________
Design:
- All components for the CNC machine have been brainstormed and designed. This was mainly done through sketches.
  
CAD:
- All CAD work has been completed for the chassis of the CNC machine on Solidworks. 

Electronics:
- Setup and tested scrap stepper motors that was found from an old machine by running G-code on CNC shield and Arduino Uno.

Work to be complete:
- Potential optimization of material use in chassis
- 3D printing and prototyping
- Running all electrical components with chassis: testing and debugging
___________________________________________________________________________________________________________________

  The design process encompassed many sketches. A full PDF of my sketches can be found here: 
  [View the file](WCPP_Design.pdf)

  A detailed version of my progress can also be found here: 

  ### WORK DONE FOR BASIC CHASSIS:
  ----------------------------------

  The project started off as a basic pen plotter. The following showcases the main steps I took to create a full SolidWorks assembly of its structure.

1. Movement:

I began by evaluating how to control the movement of the axes, drawing from my experience with other CNC machines. Opting for a standard thread and nut was the simplest and most suitable choice. With this decision made, I focused on designing how the pen would move along every axi, taking into account the stepper motor sizes and weights, as well as the space needed for the pen to cover the entire paper. An initial sketch looked something like this:

(Initial sketch)

An updated drawing could also be seen:

(Updated sketch from PDF)


Every axis would be controlled by its own stepper motor. Support beams and a thread would facilitate easy movement.


2. Design of each axis:

With a general idea of how I wanted the machine to operate, I began to do some work in CAD and assemble each of the axis individually. I played around with different sizes and shapes, aiming to make the machine as small as possible. The biggest change between the initial sketches and their new CADS was the removal of one of the support rods. CADS of each assembly for the Z,X, and Y axis could be seen below:

(Images of all three CADS)

CAD files can also be found here:
(IMPORT CAD ASSEMBLIES)


3. Assmebly

  At this stage, I began a big assembly where I could put all the axis togehter and ensure a good fit. Close-ups of how all parts attach can be found below:

   (add close up images)

   Once it all fit smoothly, I did some calculations for how large to make the rods, threads, and overall base of the structure. (This did change later on when I decided to add the watercolour attachment) With the sizing determined, an assembly was created:










   4. Attachments/Extra Features

      Other parts had to be made as well in order to ensure everything fit nicely.

      For instance, I designed and modeled a holder for the stepper motors. I realized that with a normal box support, it would be very difficult to assemble the stepper motor with the thread and rod. For this reason, I added a little "gate" that allows you to freely slide the motor in and out. A sketch and its CAD can be seen below:

(sketch and CAD)


I also had two different designs for a part that could hold the shaft of the motor to the threaded rod. Both designs and models can be seen below and both were incorporated into the final design:

(Pic 1,2,3,4)

The final attachment was a simple design to hold the pen/brush in place. Inspired by a compass, this attachement useses a screw and thread to tighten and hold it:

(image of design and CAD)


### WORK DONE FOR THE WATERCOLOUR COMPONENT
------------------------------------------------

To add depth and more complexity to this project, I decided to challenge myself to make the Pen Plotter be able to mix colours and shades through the use of water colours. Below the current work I have done to acheive this can be found:

1. Necessary Components

   I began by brainstorming what components may be needed for a machine to be able to freely use water colours. I thought back to my watercolouring days and noted that varying paints, clean water, and tissue paper was necessary in order to have untainted colours of varying shades while painting. An initial sketch of how these elements could be incoportaed are found below:

   (Sketch)

From here, I realized one big issue. Unless there was human interferance with the machine as it operated, the water used to mix the watercolours would be murky and not allow the colours to mix nicely. A solution to this? A flushing system. 

2. Flushing System

   I took inspiration from other flushing systems I have seen for watercolouring. They often looked something like this:

   (add image)

  By taking it to its simplest features, I designed my own, miniscale flushing system that could be used within the CNC. A sketch and CAD of the design can be found below:

  It is a simple spring system. To prevent any leaking, I may decide to opt for a rubber tip.

(Sketch and pic)

3. Assembly of Tray

   (wip)

4. Assmebly to entire CNC chassis

   (wip)



  


  


