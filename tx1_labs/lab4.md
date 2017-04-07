# Lab 4
The purpose of this lab is detect multiple objects in an image.


1. Modify imageDetect.py to recognize multiple bottles
For example:
1 bottle –> light up LED0
2-5 bottles -> light up LED1
6+ bottles -> light up LED2


Below figure shows the modified imageDetect.py which includes the implemented logic as described above.

![Lab 4](/tx1_labs/images/lab4.png)

2. Run imageDetect.py and pass an image to it.

```
~/detection/imageDetect.py sodagroup.jpg
```

You will notice that LED2 is turned on due to more than six bottles were detected in the given image.

Come up with your own algorithm!
