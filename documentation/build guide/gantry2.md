# Encore build guide: Print head and belt routing

## 1. Carriage setup

### Printed parts:
|Item|Qty|
|--|--|
|Print carriage body|1|

### Non-printed parts:
|Item|Qty|
|--|--|
|M3 lock nut|2|
| M3x10mm |4|
| PC4-M6 Bowden connector |1|

Screw the Bowden connector into the top of the print carriage body. This will thread directly into the plastic. 

![alt text](image-38.png)


Insert 2 lock nuts into the holes in the middle of the carriage body.

![alt text](image-27.png)



Use 4 M3x10mm bolts to attach the print carriage body to the X axis rail.

![alt text](image-28.png)
![alt text](image-29.png)

## 2. Motor installation

### Non-printed parts:
|Item|Qty|
|--|--|
| M3x6mm |8|
| 2GT pulley, 16T 5mm bore |2|
| NEMA 17 stepper| 2|

Install pulleys on motors as shown. Left motor's pulley should be upside down and approximately 4.25mm from the motor body. Right motor's pulley should be upside down and approximately 8.75mm from the motor body. Note that this may differ depending on the exact dimensions of your pulleys.
![alt text](image-30.png)

Use 4 M3x6mm bolts on each motor to attach them to the rear mid gantry frame. Leave the bolts slightly loose for now. Note: the image shows the motors in their innermost position, but for tensioning these are able to slide in and out. When initially installing belts, put the motors closer to their outer positions.
![alt text](image-31.png)

## 3. Belt routing

### Printed parts:
|Item|Qty|
|--|--|
| Belt clamp |2|

### Non-printed parts:
|Item|Qty|
|--|--|
| M3x10mm |2|
| M3 lock nut |2|
| 2GT belt | 2 sections|


The CoreXY mechanism arranges the belts in a stacked pair. Start by attaching the two belts to one side of the carrriage, and fix them in place using the belt clamp (attached with an M3x10mm bolt and lock nut).

![alt text](image-34.png)

The path of each belt is shown below:

Top belt
![alt text](image-32.png)

Bottom belt
![alt text](image-33.png)

Route the belts through the pulleys as shown in the paths above. Additional views are shown below:
![alt text](image-35.png)
![alt text](image-36.png)

When the belts are routed, clamp the other end to the carriage using another belt clamp + M3x10mm and lock nut. Trim off the excess belt as needed.
![alt text](image-37.png)

To tension each belt, pull its motor towards the center. Tighten the motor bolts to lock the tension setting.

Tensioning notes:
- Belts should be tensioned relatively firmly but not overly so. 
- Increasing tension on one belt will tilt/rotate the gantry slightly in one dimension, and tensioning the other belt will tilt it in the opposite direction. Make sure the gantry is square at the end of the tensioning process. You can confirm this by ensuring that both sides of the gantry hit the frame at the same time at min or max Y position.

## 4. Hotend and X endstop

### Printed parts:
|Item|Qty|
|--|--|
| Hotend clamp |1|


### Non-printed parts:
|Item|Qty|
|--|--|
| Bambu P1/X1 compatible hotend, fully assembled |1|
| PCB endstop | 1 |
| M3 lock nut | 3 |
| M3x10mm bolt |1|
| M3x25mm bolt |2|
| M3x30mm bolt |2|


Prior to install: Take the PCB endstop and cut off the switch. We'll use the switch only for the X endstop to save space. Test fit the switch in the print carriage (see below pic), and trim or bend the switch terminals to fit if necessary.

Remove the switch after test fitting, and solder a generous length of wire to the two outer pins. The center pin should be left unconnected.

Install the X endstop switch into its slot as shown (metal switch piece should be pointing down), and clamp down with an M3x10mm bolt and lock nut:

![alt text](image-42.png)

Insert 2 lock nuts into the outer rear holes on the print carriage:
![alt text](image-39.png)
Attach the hotend and hotend clamp onto the carriage, using 2 M3x30mm bolts in the top outer holes and 2 M3x25mm in the middle holes. The X endstop wires should pass through the small slot on the right, and the hotend wires should pass through the larger slot on the left (shown in 3rd picture below).

![alt text](image-41.png)

![alt text](image-43.png)

![alt text](image-40.png)

## 5. Print cooling fan
### Printed parts:
|Item|Qty|
|--|--|
| Print fan duct |1|


### Non-printed parts:
|Item|Qty|
|--|--|
| 4015 blower fan, 24V | 1|
|M3 lock nut |2|
|M3x10mm bolt|2|

On the hotend clamp, insert a lock nut into the slot shown:
![alt text](image-44.png)

On the print fan duct, insert a lock nut into the hole shown:
![alt text](image-45.png)

Sandwich the 4015 blower between the duct and the hotend clamp, and attach with 2 M3x10mm bolts in the locations shown:
![alt text](image-46.png)

You can route the fan wire through the cutout on the top right side, and secure using a zip tie.


Final assembly:
![alt text](image-48.png)