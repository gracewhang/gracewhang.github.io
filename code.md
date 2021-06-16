---
layout: default
title: Code
permalink: /code/
---
I'd like to use this space to share simple programs I write for random personal and research related projects I work on from time to time. I primarily use MATLAB but am hoping to also include codes written for Python and Processing. Stay tuned~



## Tomato Code [MATLAB]

Here is a [link](https://github.com/gracewhang/tomato_code) to the tomato_code repository.

This image processing script can take any .jpg image, transform it to grayscale, and threshold your image at varying levels (for version 1, it's 3 levels). For the future version 2, I'd like to give the user the ability to designate how many grayscale values they want to allow the image to have and also add the possibility of choosing colors to replace the grayscale values. But for now, here it is, plain and simple.



![Image description](/images/tomato_code.png)

If you want some music to pair this code with, I'd recommend "Hang on Little Tomato" by Pink Martini.
<center><iframe src="https://open.spotify.com/embed/track/15ffrEHBHIbXWJcsGx402o" width="300" height="380" frameborder="0" allowtransparency="true" allow="encrypted-media"></iframe>
</center>


## Determining Capacity from a Cyclic Voltammetry (a fancy way of saying area analysis)[MATLAB]
Here is a [link](https://github.com/gracewhang/Cyclic_Voltammetry_Capacity_Analysis) to the Cyclic_Voltammagram_Capacity_Analysis repository.

The premise of this work is to save me time going forward by investing some time now. In the field of electrochemistry, cyclic voltammetry (CV) is an electrochemical technqiue that experimentalists use to look at the current response of a system when sweeping the voltage in a specified range. In terms of battery materials, CVs are used to look at the potentials where redox (charge storage) occurs. CV is a powerful tool that can enable researchers like me, to study the kinetics of a material and better understand what is happening at the electrode and at what potential. One information we can also get from a CV curve is the capacity (typically reported in units of milliamp hour [mAh]), which tells us how much charge is being stored. If you look at the units of capacity: mA x h, it's current x time. The axes of a CV curve are typically shown as current (y-axis) and voltage (x-axis) but your instrument should also have the elapsed time data and thus can also be plotted as current vs time. By integrating (finding the area of) the region of each peak in a current [mA] vs time [hour] plot, we then have calculated the capacity [mAh].

![Image description](/images/CV_capacity.png)



## Creating 3D Surface Plot with 3D Scatter Plot Data [MATLAB]
3D bode analysis as a methode to understand and differentiate different charge storage mechanisms is a relatively new technique demonstrated by [Jesse Ko](https://www.researchgate.net/profile/Jesse-Ko/publication/340640541_Differentiating_Double-Layer_Pseudocapacitance_and_Battery-like_Mechanisms_by_Analyzing_Impedance_Measurements_in_Three_Dimensions/links/5f349cad458515b7291be672/Differentiating-Double-Layer-Pseudocapacitance-and-Battery-like-Mechanisms-by-Analyzing-Impedance-Measurements-in-Three-Dimensions.pdf) at John Hopkins University. Here is a [link] to the repository to make these 3D bode plots. If you aren't interested in this specific application, you can use this general code framework to make your own 3D plot. enjoy!

