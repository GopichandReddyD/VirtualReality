# VirtualReality_CS_5331_Project_1
## MyPersonalSpace Project
### Introduction
This project mainly focuses on creating a Interactive VR model. This project gave me an idea about Aframe, 3d objects. HTML and Javascripting are used in this project. Tools used in this project are Visual studio code and Brackets.Modes present are NON-COVID and COVID. 

### Video Demonstration:

![alt text](https://youtu.be/h0_7AokOhbw)

### Theme:
•	Theme of the project is to Create my personal space and add the changes which took place because of covid.

### Description:
 
•	Languages: HTML, A-Frame.

• Tools: Visual studio code, Brackets.

•	Walls are created using given different colours. sample code is as follows:
```
<a-entity static-body="" geometry="width:25;height:14" position="-14.657 6.948 2.489" rotation="0 90 0"
        material="roughness:1;src:images/WhiteWall.jpg"></a-entity>    
```

•	Ceiling and flooring are also done as the same way above by changing the rotation direction and position. sample code is as follows:
```
<a-entity rotation="0 0 0" position="-5.257 12.889 5.497" color="#888" scale=".007 .003 .007"
        obj-model="position:-5.257 12.889 5.497;obj:#CeilingfanO; mtl:#CeilingfanM" class="intersectable">
        <a-animation attribute="rotation" dur="3000" from="0 0 0" to="0 360 0" easing="linear" repeat></a-animation>
      </a-entity>
```
•	I used objects models to fill the room and colours were modified. some objects were created by me. Demo code is as follows:
```
  <!--- Bed --->
      <a-obj-model id="bed" src="assets/bed.obj" position="2.512 0.254 4.201" scale="0.04 0.04 0.05" material=""
        rotation="0 180 0" color=#362626 class="intersectable">
      </a-obj-model>

      <!---Chair-->
      <a-obj-model id="chair" src="assets/chair.obj" position="-10.255 0.424 -1.331" scale="0.04 0.04 0.05" material=""
        rotation="0 270 0" color=#362626 class="intersectable">
      </a-obj-model>

      <a-entity>
        <!--- dog --->
        <a-obj-model id="Dog" src="assets/Dog.obj" position="-9.721 0.424 -7.693" scale="0.2 0.2 0.3" material=""
          rotation="0 217.991 0" color=#362626 class="intersectable">
          <a-animation attribute="rotation" dur="3000" from="0 0 0" to="0 45 0" easing="linear" repeat></a-animation>
      </a-entity>
  ```
  
  ```
  <!--- Laptop Table -->
      <a-box position="-12.153 1.885 -3.000" rotation="0 90 0" scale="0.2 3 0.2" color="#362626" shadow></a-box>
      <a-box position="-12.153 1.885 1.000" rotation="0 90 0" scale="0.2 3 0.2" color="#362626" shadow></a-box>
      <a-box position="-14.153 1.885 -3.000" rotation="0 90 0" scale="0.2 3 0.2" color="#362626" shadow></a-box>
      <a-box position="-14.153 1.885 1.000" rotation="0 90 0" scale="0.2 3 0.2" color="#362626" shadow></a-box>
      <a-box position="-13.920 3.254 -1.084" rotation="0 90 0" scale="8 0.3 4.2" color="#362626" shadow></a-box>
  ```
  
  ### Objects:
  
  • Walls
  • Bed
  • chair
  • sofa
  • tv
  • speaker
  • AC
  • fan
  • laptop
  • Monitors
  • Keyboard
  • Tables
  • Switches
  
  ### Screenshots of the model are displayed below:
  ![alt text](https://github.com/GopichandReddyD/VirtualReality/blob/main/VirtualReality_Project_1/Screenshots/SpaceAround.png)
  ![alt text](https://github.com/GopichandReddyD/VirtualReality/blob/main/VirtualReality_Project_1/Screenshots/SpaceAround2.png)
  ![alt text](https://github.com/GopichandReddyD/VirtualReality/blob/main/VirtualReality_Project_1/Screenshots/SpaceAround3.png)
  ![alt text](https://github.com/GopichandReddyD/VirtualReality/blob/main/VirtualReality_Project_1/Screenshots/SpaceAround_CovidMode.png)
  ![alt text](https://github.com/GopichandReddyD/VirtualReality/blob/main/VirtualReality_Project_1/Screenshots/SpaceAround_NightMode.png)
  
  ### Try it out:
  
  https://gopichandreddyd.github.io/VirtualReality/VirtualReality_Project_1/
  
  ### Conclusion:
   This project gave me a great oppurtuniy in learning to design virtual spaces. Demonstrating an idea using 3D view will be the best part in future. I would like to come back and improve object qualities, areas and next rooms of the project.
