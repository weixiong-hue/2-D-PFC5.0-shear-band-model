1. Overview        

The 2D PFC model code used to simulate the stick-slip dynamics of the shear band is organized into two types of files, which are placed in folders labeled "computational code" and "graphics file", respectively.        

In the "computational code" folder, the files used for calculations are labeled as "Do_all.p2dat", "Create_sample.p2dat", "Servo.p2dat", and "Start_shear.p2dat". The reading and execution order of these files is from "Do_all.p2dat", "Create_sample.p2dat", "Servo.p2dat" to "Start_shear.p2dat", please run them under version 5.0 of PFC2D. Before running, make sure to create a new project file and then add these calculation files to the project. A basic understanding of PFC 5.0 is required for this process. The official PFC software and resources are available at https://www.itascacg.com/.    

In the "graphics file" folder, the files with the ".dxf" and ".dxfbak" extension are graphic files that will be imported into the PFC2D code to define the dimensions of the computational domain and the corrugated plates.  These files do not require any modifications unless changes to the shear band model size or the corrugated plate design are needed.   

Overall, these codes are designed to generate a shear band simulation under constant confining pressure and constant shear velocity. They can replicate the behavior of a natural shear band and output the effective friction coefficient curve, enabling analysis of the stick-slip dynamics of the shear band. 
The code does not require any dataset input and can be run on a standard computer without strict hardware requirements. However, if the shear band model contains a large number of particles, better computer hardware performance may be needed. 

2. System requirements

Please run this code in the official version 5.0 of PFC2D (official website: https://www.itascacg.com/). There are no specific requirements for the operating system or runtime environment; the author ran this code on Windows 10.

3. Installation guide

Installing PFC 5.0 is straightforward, and detailed installation instructions can be found on the official website at https://www.itascacg.com/. Typically, the installation time on a standard computer does not exceed one hour.

4. Demo

Run the file "Do_all.p2dat," which will sequentially call the other three files: "Create_sample.p2dat," "Servo.p2dat," and "Start_shear.p2dat." This code can output the effective friction coefficient of the shear band model over time under specific confining pressure and shear rate conditions. Depending on the number of particles, the runtime of the code may range from 10 minutes to 7 days.Running and modifying the code requires some basic knowledge of PFC5.0, which can be found in the PFC5.0 user manual (https://www.itascacg.com/).
