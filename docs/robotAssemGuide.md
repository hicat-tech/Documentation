### <font size=40>__The Robot kit Assembly Guide__</font>

![Image](/img/robotAssemGuide/robotAssem1.png)

Like the picture shows, the Livera Robot kit ccomes with several conponents that you need you assemble and make it to a fully functional robot. This toturial would get you through all the process of `physical building and wiring,` it might take around `25 minutes` to make the robot alive. Clear up your desk, unpack the Robot kit and let begin the journey.

#### __Parts list__

![Image](/img/robotAssemGuide/robotunbox.jpg)
![Image](/img/robotAssemGuide/partlists.jpg)

The Livera Robot kit comes with following parts:

- __Boards:__ HICAT.Livera Boardx1 Livera Motor Driver Boardx1
- __Camera:__ Livera Camera Extend Cablex1 Livera Camera Modulex1
- __Storage:__2G SD Card with firmware built in
- __Guidebook:__ Livera GuideBookx1 Livera Robot Assembly GuideBookx1
- __Power:__ 9V Lipo Battery and Bat Carrier
- __Motor:__ E-MAX SERVOx1 DC Gear Motor set(Motor + Motor Carrier + Wheels)x2
- __Structure bits:__ Robot Base Acrylic Panels set, Omni-directional Wheel Set 
- __Screws:__ M2x15(+6)mm Nylon Studx4, M2x6mm Nylon Studx4, M2x6(+6)mm Nylon Studx8, M2x10(+6)mm Nylon Studx8, M2 Nylon Nutx4 
- __OUTPUT:__ LASER Beanx1
- __Accessories:__ Stickersx1, USB Cablex1, Screwdriver(+,-)x1



#### __Video Tutorial__
We've also created a video toturial to give you a more detailed, much clear step by step toturial, would help you with:

- Pyhsical Assembly
- Webapp Guide

<pre>
	<iframe width="560" height="315" src="https://www.youtube.com/embed/Evkkf7BJYWA" frameborder="0" allowfullscreen></iframe>
</pre>

#### __Step 1: Base panel build__

![Image](img/robotAssemGuide/robotAssem2.jpg)

Unpack the Livera Robot kit package, Find out the following conponents in order to build the base panel of the Robot.

- __Robot Base Acrylic Panel x1__
- __DC Motor + Motor Carrier x2__
- __Omni-directional Wheel Set x1__
- __M2x15(+6)mm Nylon Stud x4__
- __M2x6mm Nylon Stud x4__
- __M2x6(+6)mm Nylon Stud x4__
- __M2 Nylon Nut x4__

__Notice:__ All the Stud could be install by hand, doesn't require and tools.
__`Caution:`__ Don't make it too tight while screwing with the `Livera and Livera Motor Driver`, might have a small chance to cause damage to the board if you screw it too hard. 
 

![Image](img/robotAssemGuide/robotAssem3.jpg)

Assemble up the `Omni-direction Wheel Set` like the picture shows, then close up with the `Cover bit`, waiting for screw on the `Base Panel.` 

![Image](img/robotAssemGuide/robotAssem4.jpg)

![Image](img/robotAssemGuide/robotAssem5.jpg)

- __Install the motor on base panel:__ carefully place the `M2 Nut` onto the `Motor Carrier's slot`, than catch the `DC Motor` and match to the hole on the `Base Panle`, notice to keep the `+` sign on top as the left top of the pic shows, using `M2x6(+6) Stud` to screw through from the other side of the panel.
- __Install the Structure bit:__ place the `M2x15(+6) Stud` on top of the `Base panel`, then let the `6mm screw bit` through the hole and screw into the `M2x6mm Stud.`

#### __Step 2: Body build__

![Image](img/robotAssemGuide/robotAssem6.jpg)

- __Install the Livera Motor Driver:__ simply place by matching to the `Stud.`
- __Install the Structure bit:__ Screw `M2x10(+6)mm Stud` on top.

__`Caution:`__ Don't make it too tight while screwing with the `Livera and Livera Motor Driver`, might have a small chance to cause damage to the board if you screw it too hard. 


![Image](img/robotAssemGuide/robotAssem7.jpg)

- __Install HICAT.Livera with Extend Cable:__ carefully stack `Livera` on top of `Livera Motor Driver,` do check for the `I/O ports` and the `outline` to see weather it is matched to the `Livera Motor Driver.`
- __Install the Structure bit:__ Screw `M2x10(+6)mm Stud` on top of Livera.

__`Caution:`__ Don't make it too tight while screwing with the `Livera and Livera Motor Driver`, might have a small chance to cause damage to the board if you screw it too hard.

#### __Step 3: Top build__

![Image](img/robotAssemGuide/robotAssem8.jpg)

- __Install the top Acrylic Panel:__ place the `Top Acrylic Panel`, fix the panle by screw the `M2x6(+6)mm Stud` on top.
- __Stick the Power case and Servo:__ unpack the `3M Sticker,` stick the conponents as the image shows.
- __Connect Power:__ connect the 2.54mm Power connector from `Power case` to `Livera Motor Driver.`


![Image](img/robotAssemGuide/robotAssem9.jpg)

- __Install the Camera pan-tilt:__ screw the Servo Arm Set form the `EMAX Servo set` on the `Camera Pan-tilt.`
- __Install Camera Module:__ carefully place the camera module on the `Acrylic Camera Pan-tilt`, using `M2 Rivet` to fix it.
- __Install Camera Extend Cable and Laser Bean:__ install the conponents as the picture shows, notice that the `direction` of the camera module should be `match together` according to the `indicate drawings.`

#### __Step 4: Wiring__

![Image](img/robotAssemGuide/robotAssem10.jpg)

- __Wiring:__ wire up all the electronics(Motors, Laser, Servo) as the picture shows, for the `DC Motor` wring, you would need to use the screwdriver to fix the wire into the adapter.
- __Install SD card:__ put the `SD card` into the SD slot.

![Image](img/robotAssemGuide/robotAssem11.jpg)

- __Install Battery:__ put the `9v chargable battery` into the `Power Case.`
- __Power up to init the Servo:__ switch on the `Power Switch` From the Motor Driver, wait until heard `two movement` from the `Servo,` then put the `Camera Pan-tilt` on the `Servo` in a `horizon direction,` screw it up using the smallest screw from the Servo Box.
- __Enjoy:__ pick up you cell phone, connect to the `Livera's wifi`,

```
ssid:hicat_xxxxxx
passward:88888888
```

 then open `chrome browser`, go to the web page 

```
http://192.168.1.1/mmc/webapp/index.html
``` 


- Switch the top video switcher to `MJPG MODE`, click `LiveView`, if the image flipped, you could change it within `QUALITY,` we suggest you to chose `240p/15fps.`

- Click `ROBOT` to open the control panel, Try press forward button, if you see the robot `spinning` or `move back,` you could adjust the wiring by switch the `DC motor` wire from the adapter.