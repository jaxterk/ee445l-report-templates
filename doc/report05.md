# EE 445L Lab 5 Report

- 'Firstname Lastname (eid123)'
- 'Firstname Lastname (eid123)'

Objectives
----------

-   What did you do to complete this lab?
-   What components were you learning about?
-   Why do you think we made you do this lab?
-   Aim for 5-12 bullet points

Software Design
---------------

// Create a call graph and dataflow graph to accurately reflect your code.  
// An example of a dataflow graph is included at the end of the procedure  
// section. [draw.io](draw.io) and [inkscape](inkscape.org) are some options for  
// creating .svg files.  

// If you made a program to convert musical data to the data structure used  
// for the song in your lab, please provide a short description and include  
// the program in your GitLab repository.

// See figures 5.8 and 5.9 in the lab document  

![image](callgraph.png)  
![image](dataflow.png)  
// Don't forget to change the file extensions if necessary

Hardware Design
---------------

// Create a circuit diagram of your final hardware design in the PCB editor  
// of your choice. Make sure to include any extra diodes and exact resistor  
// values.

![image](circuit.png)  
// Don't forget to change the file extensions if necessary

Measurement Data
----------------

### Show the data and calculated resolution, range, precision, and accuracy of the DAC. (procedure 3)

---------------------------------------------
|			| Calculated	| Experimental	|
---------------------------------------------
| Resolution|				|				|
| Range		|				|				|
| Precision	|				|				|
| Accuracy	|				|				|
---------------------------------------------

// Show your work here
#### Resolution

#### Range
// Get the maximum value  

#### Precision

#### Accuracy
// Check the output for various levels, for example all of the powers of 2  

2. Show the experimental response of DAC including the signal-to-noise ratio. (procedure 4)

![image](2_oscope.png)

3. Show the results of the debugging profile. (procedure 5)

![image](3_oscope.png)
// or a screenshot in keil

4. Show +5V voltage, voltage RMS (which will be very small) and current, with and without the music playing. (procedure 7)

![image](5_oscope_no_music.png)  
![image](5_supply_no_music.png)  
![image](5_oscope_with_music.png)  
![image](5_supply_with_music.png)  
// You could also show multimeter readings

Analysis and Discussion
-----------------------

1. *Briefly describe three errors in a DAC.*

	Answer goes here

2. *Calculate the 'data available' and 'data required' intervals in the SSI/DAC interface. Use these calculations to justify your choice of SSI frequency.*

	

3. *How is the frequency range of a spectrum analyzer determined? In other words, what property of the spectrum analyzer determines the maximum range of frequencies that it can analyze?*

	

4. *Why did we use the TPA731 rather than simply driving the speaker directly from the DAC?*

	

