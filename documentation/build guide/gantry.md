# Encore build guide: Gantry

## 1. Front idler block pulleys

### Printed parts:
|Item|Qty|
|--|--|
|Left front idler block|1|
|Right front idler block|1|

### Non-printed parts:
|Item|Qty|
|--|--|
|M3x20mm bolt |2|
|M3 lock nut|2|
| F623 bearing |4|

![alt text](image.png)

For each front idler block:
- Insert 2 F623 bearings into the pulley slot. The flanges should be facing away from each other.
- Secure with an M3x20mm bolt and lock nut underneath.




## 2. Rear idler blocks and mid frame

### Printed parts:
|Item|Qty|
|--|--|
| Rear idler spacer |2|
| Rear left idler block |1|
| Rear right idler block |1|
| Rear mid frame | 1|

### Non-printed parts:
|Item|Qty|
|--|--|
|M3x30mm bolt | 4|
|M3 lock nut| 4|
|F623 bearing| 12|

For each rear idler block, install pulleys as shown in the image below. Use M3x30mm bolts inserted from the top of the part. For the double stacked pulley, the order is:
1. F623 (flange on top)
2. F623 (flange on bottom)
3. Rear idler spacer
4. F623 (flange on top)
5. F623 (flange on bottom)

![](image-1.png)

Install the rear midframe underneath and secure the M3x30mm bolts via 2 M3 lock nuts.
![](image-2.png)

Repeat the same steps for the other side; the resulting assembly should look like the following:
![](image-3.png)


## 3. Upper frame attachment

### Printed parts:
|Item|Qty|
|--|--|
| Top chassis |1|


### Non-printed parts:
|Item|Qty|
|--|--|
|M3x12mm bolt | 12|
|M3 lock nut| 12|

Insert 4 lock nuts into the top slots of the rear left and right idler blocks
![alt text](image-11.png)

Attach the top chassis to the rear idler assembly using 8 M3x12mm bolts:
![alt text](image-12.png)

Attach the left/right front idler blocks to the top chassis using 4 M3x12mm bolts and 4 lock nuts:
![alt text](image-13.png)


## 4. Linear rail installation

### Non-printed parts:
|Item|Qty|
|--|--|
| 150mm MGN9 rail with MGN9C carriage |2|
|M3x10mm bolt | 8|
|M3 lock nut| 8|

Note: The linear rails should be properly prepped and greased before assembly. See this guide for the necessary steps: https://docs.ldomotors.com/guides/rail_grease_guide

Install the right side linear rail using 4 M3x10mm bolts and 4 lock nuts. Note: use the triangular tabs on the front/rear right idler blocks to align the rail.
![alt text](image-14.png)

Install the left side linear rail in the same fashion. NOTE: Leave the bolts loose for now; final tightening will be done when the X gantry is installed.
![alt text](image-15.png)

## 5. X gantry assembly
### Printed parts:
|Item|Qty|
|--|--|
| Gantry body |1|
| Gantry left end |1|
| Gantry right end |1|

### Non-printed parts:
|Item|Qty|
|--|--|
|M3x25mm bolt | 4|
|M3x12mm bolt | 4|
|M3x30mm bolt |4|
|M3 lock nut| 8|
| 150mm MGN9 rail with MGN9C carriage | 1 |

Install 2 M3x25mm bolts and F623 bearings as shown onto the gantry left end:

![alt text](image-16.png)

Secure the left end onto the gantry body using 2 lock nuts:
![alt text](image-17.png)

Repeat the same steps for the right end:
![alt text](image-18.png)
![alt text](image-19.png)

![alt text](image-20.png)

Use 4 M3x12mm bolts and 4 lock nuts to secure the 150mm MGN9 rail to the gantry body:
![alt text](image-21.png)

Use 4 M3x30mm bolts to secure the X gantry to the Y rails:
![alt text](image-22.png)

After the X gantry is installed, run it back and forth to each end, and tighten the bolts on the left Y rail. Make sure movement is smooth throughout the entire Y travel.
![alt text](image-23.png)

## 6. Y endstop installation

### Printed parts:
|Item|Qty|
|--|--|
| Y endstop mount |1|

### Non-printed parts:
|Item|Qty|
|--|--|
|M3x8mm bolt | 2|
|M3x10mm bolt |2|
|M3 lock nut| 4|
| PCB endstop | 1 |

Install a PCB endstop onto the Y endstop mount using 2 M3x8mm bolts and 2 lock nuts:
![alt text](image-24.png)

Install the Y endstop onto the top chassis using 2 M3x10mm bolts and 2 lock nuts:
![alt text](image-25.png)

Full assembly:
![alt text](image-26.png)