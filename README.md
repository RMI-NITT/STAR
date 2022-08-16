# STAR
System for Tracking Animals using Radar 

### Introduction
In the course of the last century alone, the planet witnessed the extinction of 18 species of animals. A multitude of wildlife sanctuaries have been established around the globe with the sole purpose of protecting and preserving wildlife in their natural habitat. Despite their eﬀorts, acts of poaching and hunting continue to threaten the existence of many animal species. Locating and monitoring the movement and vitals of the animals in reserves are challenging. 

### Existing Technology
Some of the existing models for the purpose of tracking wild beings use methods like microchips and GPS which require a physical device to be worn by the animal at all times. This is not feasible as these devices are prone to damage, usually heavy and cannot be used for smaller animals. Furthermore, it gives no information with respect to monitoring of heartbeat and breathing rate.

### Proposed Solution
This project proposes the use of Frequency Modulated Continuous Wave radar to send and analyse signals to detect and estimate respiration and heartbeat frequencies. Being capable of measuring vital signs(through non-contact methods) and having a wider ﬁeld, it is more advantageous than the existing alternatives. Through its implementation the following can be acheived:

  1. Detect and measure vital signs of animals.
  2. Tracking both animal and human movements to prevent poaching and hunting in wildlife sanctuaries.

Weather is not a constraint and this system can work all day long. The radar technology gives real time tracking of the vital signs of the animals by emitting waves and analyzing the reflected waves. This eliminates the demerits of wearing a physical device and the time taken for this estimation is less due to high-end signal processors.

#### FMCW 

##### Triangulated FMCW
![fmcw_prinzip(2)](https://user-images.githubusercontent.com/83502978/179925186-79d7870a-0c61-42b2-a17a-f8900c74a2b1.png)

##### Sawtooth FMCW
![7028 chirp2 gif-480x0](https://user-images.githubusercontent.com/83502978/179922845-af3ce434-1fb9-4b69-a0c6-ca684d457351.png)

##### Distance and Velocity Calculations

![image](https://user-images.githubusercontent.com/83502978/181252806-a2399673-33e2-4776-926b-03557532cede.png)

_Note: This project proceeded with triangulated FMCW wave since it had some resources to refer to, during that point of time._

#### Hardware

![20220815_191725](https://user-images.githubusercontent.com/83502978/184810478-cf366c96-4615-4f2f-8471-05d8de3c921e.jpg)
![20220815_191742](https://user-images.githubusercontent.com/83502978/184810541-afed3504-fd1d-49bc-93a6-04da424c5f09.jpg)

* https://www.ti.com/product/IWR6843AOPEVM/part-details/IWR6843AOPEVM

### Progress till now
Frequency Modulated Continuous Wave technology is by itself a topic which is actively in research around the world. There are very few resources available for the intention of this problem statement and even if they are found, they generally tend to be too complicated. 

Simulations for heartbeat and respiration rate were modelled in MATLAB. It was also figured out that this radar technology also had applications in motion tracking, contour detection, area scanning, etc. 

The hardware from Texas Instruments, IWR6843AOPEVM, was utilized in this project. Many guides, videos and articles were referred for understanding its working and the potential it holds.
 
 Works are still being held on by RMI members in this project.
 
 ### Key Contributors 
 - [Madhav R](https://github.com/madE03)
 - [Girish K](https://github.com/girish-2001)
 - [Sunkara Vikash](https://github.com/Vikash2024)

### Reference Links
#### FMCW References
* https://www.iist.ac.in/sites/default/files/people/IN14204/Lecture%2022-23-FMCW%20Radar.pdf
* https://www.tutorialspoint.com/radar_systems/radar_systems_fmcw_radar.htm
* https://training.ti.com/intro-mmwave-sensing-fmcw-radars-module-1-range-estimation
#### Hardware References
* https://e2e.ti.com/support/sensors-group/sensors/f/sensors-forum/1037712/iwr6843aopevm-iwr6843aopevm-which-additional-boards-required?tisearch=e2e-sitesearch&keymatch=IWR6843AOPEVM#
* https://www.ti.com/lit/ug/swru546d/swru546d.pdf?ts=1645507811467&ref_url=https%253A%252F%252Fwww.ti.com%252Ftool%252FIWR6843ISK-ODS
* https://www.ti.com/tool/IWR6843AOPEVM



