# Compact 3D printed enclosure/sensormount for a barebones IMX585 [Cinepi](https://github.com/cinepi/cinepi-raw) camera.

![Everything](https://github.com/user-attachments/assets/079fca57-33fe-423a-bf2a-d652175576f4)

## Features:

    • Spring adjustable C-Mount
    • Raw recording Capabilities (4K 12Bit - 1/1.2 inch sensor)
    • Internal Storage on NVME 2280 SSD
    • NPF battery compatibility
    • Display via Smartphone
    • Lots of mounting points for addons

## Software

>	[Cinemate](https://github.com/Tiramisioux/cinemate/tree/main) by Tiramisioux - A simple gui built ontop of cinepi-raw for control via wifi or screen <br>
>	 [Cinepi-raw](https://github.com/cinepi/cinepi-raw) by Schoolpost - Image capture and control interfaces - Makes raw recording possible
>	<br> <br>
>	Thanks for providing the software for us ♥

## Addons (for now):
![Addons](https://github.com/user-attachments/assets/83abdb2c-125f-46df-810e-0043b5c8d49c)

    • Grip
    • Adaptor for a DJI ronin RS3 phoneholder

## Printing Materials

    • Use a material of your liking for most of the parts
    • TPU of softness of at least 88A (Springs and Rubbercover need to be printed from TPU)



## BOM:
**1x CinepiCamera_Straight_Mainbody.stl**<br>
	&nbsp;&nbsp;&nbsp;&nbsp;6x ruthex - RX-1/4-20x12,7 – Quarter inch threaded inserts<br>
	&nbsp;&nbsp;&nbsp;&nbsp;8x ruthex – RX-M3x5_7 – M3 threaded insert short<br>
1x Adjustablemount_C_Springs_2 (assembly)<br>
	&nbsp;&nbsp;&nbsp;&nbsp;1x SE-SB8M-IMX585 (notes in assembly guide)<br>
	&nbsp;&nbsp;&nbsp;&nbsp;**3x Adjustablemount_C_Springs_TpuSpring.stl** !Caution print in 88A or similar TPU!<br>
	&nbsp;&nbsp;&nbsp;&nbsp;3x M2x10 flat head screw<br>
	&nbsp;&nbsp;&nbsp;&nbsp;**1x Adjustablemount_C_Springs_Rubbercover.stl** (notes in assembly guide)<br>
	&nbsp;&nbsp;&nbsp;&nbsp;**1x Adjustablemount_C_Springs_Gluebase.stl** (notes in assembly guide)<br>
	&nbsp;&nbsp;&nbsp;&nbsp;**1x Adjustablemount_C_Springs__Filterholder.stl** (notes in assembly guide)<br>
	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	1x IR-Cut Filterglass (18x15mm)<br>
	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;  2x M2x4 Flat head screws<br>
8x M2x4 Flat head screws<br>
**1x CinepiCamera_Straight_Batterycompartment.stl**<br>
	&nbsp;&nbsp;&nbsp;&nbsp;1x ruthex – RX-M3x5_7 – M3 threaded insert short<br>
	&nbsp;&nbsp;&nbsp;&nbsp;2x 2.6mm banana plug (notes in assembly guide) – eg. RS: 2080217<br>
	&nbsp;&nbsp;&nbsp;&nbsp;2x ISO 4762 M2x8 cylindrical head screw<br>
	&nbsp;&nbsp;&nbsp;&nbsp;1x CK1408 dcdc 5V stepdown converter<br>
	&nbsp;&nbsp;&nbsp;&nbsp;1x Raspberry Pi 5 B 8GB<br>
	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	1x Pineboards HatDrive! Bottom<br>
	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	1x Samsung 970 EVO Plus - 2 TB 2280 SSD (or alternatives if compatible)<br>
	&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;	1x Raspberry Pi active cooler for RPI5<br>
	&nbsp;&nbsp;&nbsp;&nbsp;	4x ISO 4762 M2.5x16<br>
	&nbsp;&nbsp;&nbsp;&nbsp;**1x CinepiCamera_Batterydoor.stl**<br>
	&nbsp;&nbsp;&nbsp;&nbsp;1x ISO 4762 M3x10 cylindrical head screw<br>
4x ISO 4762 M3x10 cylindrical head screw<br>
**1x CinepiCamera_Straight_Top.stl**<br>
	&nbsp;&nbsp;&nbsp;&nbsp;3x ruthex - RX-1/4-20x12,7 – Quarter inch threaded inserts<br>
	&nbsp;&nbsp;&nbsp;&nbsp;4x ruthex – RX-M3x5_7 – M3 threaded insert short<br>
4x ISO 4762 M3x10 cylindrical head screw<br>
<br>
Sony NP-F750 batteries (or other sizes of batteries – NP-F750 is flush with the camera)<br>
<br>

## BOM Addons:

**1xCinepiCamera_Straight_Grip.stl**<br>
	1x ruthex - RX-1/4-20x12,7 – Quarter inch threaded insert<br>
4x ISO 4762 M3x10 cylindrical head screw<br>
<br>
**1x CinepiCamera_Straight_RoninPhoneholder.stl**<br>
	1x ruthex - RX-1/4-20x12,7 – Quarter inch threaded insert<br>
1x Tripod screw with cylinder head (or fitting alternatives)<br>
<br>
<br>

## Assembly guide

## Converting the CS Mount on the IMX585 Board to C Mount

![CS-Mount Soho](https://github.com/user-attachments/assets/b97c1c37-a97e-40ba-9476-59c61ec7b16d)
![CS-Mount Soho Back](https://github.com/user-attachments/assets/ab3c3305-38e3-424e-b826-92cbec27d716)
<br><br>
>Remove the M2 screws from the back of the IMX585 PCB<br>
>Preheat your 3D printer bed to the maximum level supported by it (without destroying your printer bed) - I used 120 °C<br>
>Place down the aluminum mount face down onto the hotbed and leave it there for a few minutes to weaken the glue<br>
>
>Use a sharp prying tool to remove the aluminium mount from the pcb while still warm - Start prying on the edges - Dont use too much force!<br>
<br>

![Cs-CmountIMX585_5](https://github.com/user-attachments/assets/613d958d-5dbb-4cd8-9c25-6b4968bf080a)

>Use a M2 screw (or tap) and form the threads on the **Adjustablemount_C_Springs_Gluebase.stl** (pictured red)
>Use glue or silicone (neutral cure to not damage the aluminium?) and fix it to the removed CS mount
<br>

![Filterholder Exchangable](https://github.com/user-attachments/assets/420435e9-058b-40bf-b899-7798f06234d1)

>Cut the IR Filterglass to size (18x15mm)
>Glue it to the **Filterholder Exchangable.stl**

![Cs-CmountIMX585_4](https://github.com/user-attachments/assets/988a0cd6-8c86-4557-a9ce-6c680f684ac8)

>Use three **Adjustablemount_C_Springs_TpuSpring.stl** and M2x10 screws and fix the sensor to the mount<br>

![Cs-CmountIMX585_2](https://github.com/user-attachments/assets/e05596cd-5226-4206-92dd-81cf4713ce1c)


>Add the **Adjustablemount_C_Springs_Rubbercover.stl** by using either M2x8 screws or glueing it to the sensor board<br>
>Use electrical tape or similar to remove light leaks after adjusting the mount<br>

<br>
<br>
<br>


Shield: [![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
