# PLC-Basics with LinkedIn Learning
This repository documents my personal learning journey using LinkedIn Learning courses to familiarize myself with PLC Basics.

**Disclaimer**: I do not own the copyright to the course videos or original exercise files. All rights belong to LinkedIn Learning and their respective authors. 

**Repository Content**: The files in this repository are **my own practice and notes** created while following the course. They are shared here to demonstrate my progress and understanding.


<details>
<summary> Intro to PLC and Automation Course </summary>
<details>
 <summary> 1. Introduction to PLC and Industrial Automation </summary> 
  Used to control operations and processes often in factories or industrial settings.

  What does an industrial automation system consist of?
  > Include eveyrhting involved to complete the automation task or process.
  * Controllers (PLC - programmable logic controller, DCS - distributed control systems)
  * Field devices (sensors, actuators, motors, cameras)
  * Industrial communication/networking
  * Human-machine interface (HMI)
  * SCADA (supervisory control and data acquisition software)
  * Personal computers (PC)

  For example, general flow can look like: process (sensors and devices) -> controller (PLC) -> software (SCADA)

  ### Industrial Automation Levels

  3 main levels: field level, control and communication level, management level.
  
  Field level: sensors and devices used on the field itself (i.e. factory floor).

  Control and communication level: controls flow of data from the field level to the management level based on the logic of the PLC or DCS

  Management level: software programs to process, control, and gather data in real time. 
  > ex. SCADA software
  * SCADA connects field devices, controllers, and equiptment to facilicate the real-time data monitoring

  ### Overview of Industrial Controllers
  Details the movement and steps within the automation process

  Industrial controllers receive sensor inputs and make a decision based on that data and the instructable program. 
  * Many types of PLCs and DCSs on the market (Allen-Bradley, Omron, Siemens)

  ### PLC Programming Languages
  Text based and graphical are the two main subsections for languages
  * Text based: instruction list, structured text
  * Graphical: **ladder logic diagram (LLD), function block diagram (FBD)**, sequential function chart (SFC)

</details>

<details>
 <summary> 2. PLC Programming (Ladder Logic) </summary> 

  ### Ladder Logic Programming
  Ladder Logic Programming name comes from the visual aspect of the program - it looks similar to a ladder when completed.
  * Inputs are written on the left side of the ladder --| |--, and outputs are on the right side of the ladder --{ }--
  * The rails indicate the rails of the power supply (can be positive, ground, negative)

  How is a ladder logic program read?
  * Read from LEFT to RIGHT, and TOP to BOTTOM!
  * Each line is called a "rung", which represent how the program is designed.
  * Each input and output is called an instruction.

  ### Input Instructions
  Input instructions are writted as two bars facing each other, but there are two main types (boolean types):
  * Examine if Closed (XIC)
  * Examine if Open (XIO)
  * If we have two switches, we can add them using AND or OR (series or parallel).
  * Recall CSE 100, seems similar to logic diagrams


  ### Output Instructions
  Output instructions are written as parenthases with a space in between
  * Output instructions are activated when the input instructions on that rung are true on that rung.
  * A rung can work with only an output, but each input instruction must have at least one output.
  * If there are multiple output instructions to one input instruction, they are added in parallel. 
  
</details>

<details>
  <summary> 3. Hands-On Example </summary> 

  ### Push Button and Light
  We have a push button as our input and a green LED as out output, how can we connect these using ladder logic?

  My attempt: |----| |----{ }---| -> where the right most and leftmost | are the rails, the | | on the left is the button input and the { } on the right is our LED
  * The tutorial has the same drawing as I have, just done better and then she goes though a software demo.

</details>
</details>

<details>
  <summary> Learning PLC Ladder Logic </summary>
<details>
  <summary> 1. PLC Programming </summary>

  
</details>
</details>
