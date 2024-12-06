This software tool enables users to obtain design parameters for Helmholtz coils for a required homogeneous magnetic field domain, when provided either the magnetic field domain cross-sectional diameter or the coil spacing required for the device.
Development environment: Visual Studio 2022 Community Edition
Operation system: Microsoft Windows
Development language: C#
Instructions for users: 
Step1: Download the zip file and extract it. 
Step2: Double click on **Helmholtz Coils Design Tool for Homogeneous Magnetic Field.exe**
Step3: In the interface, enter your desired Helmholtz Coils shape, either circular or rectangular, other odd coil shapes are not considered in the version due to their limited applicability. 
Step4: Enter the value of the cross section diamater (in mm) for your target domain where magnetic field will be generated. Target domain may be a circular, cylinderical,spherical, cubical or others. 
Step5: If you do not specify the target domain, then specify a desidred space between the Helmholtz Coils, as this will determine the minimal space required by your device. 
Step6: Enter the diameter of the copper wire you intend to use, this will vary depending on how much driving current you will input to the coil, and the cost of the wires etc. Users may choose wire diameters accordignly. 
Step7: Click on **Compute**
Step8: The software tool will output parameters that ensure the magnetic field generated in the domain will be as homogeneous as it can be. 
