# YagiWifi
Yagi antenna for wifi 2.4Ghz with 10.5dB Gain, modelled in HFSS and then created the prototype.


This is the HFSS Model: 

![alt text](https://github.com/stefano0293849/YagiWifi/blob/master/cad.png)


This is the Real and immaginary Impedence of the antenna:

![alt text](https://github.com/stefano0293849/YagiWifi/blob/master/impedence.png)


As we can see in the HFSS simulation the antenna will have 10.5dB of Gain, this is the radiation graph:

![alt text](https://github.com/stefano0293849/YagiWifi/blob/master/rad.png)

this is the S11 (Scattering seen from port 1)

![alt text](https://github.com/stefano0293849/YagiWifi/blob/master/S11.png)

And this is the created model (if you don't know how a yagi antenna is made, remember to leave a 1mm space between the two elements in the second posizion, and connect one to the center of the coxial cable, and the second one to the ground of the coaxial cable, the other elements are not connected to anything, they are just sit on the plastic bar):

![alt text](https://github.com/stefano0293849/YagiWifi/blob/master/measure.jpg)

After that i have added the coaxial cable ( yes i did a little mess)


![alt text](https://github.com/stefano0293849/YagiWifi/blob/master/cable.jpg)


And results with the original Alpha antenna of 5dB and with the Yagi Uda antenna, Urra!

![alt text](https://github.com/stefano0293849/YagiWifi/blob/master/yagi.png)

![alt text](https://github.com/stefano0293849/YagiWifi/blob/master/alpha.png)



