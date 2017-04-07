# Lab 5
The purpose of this lab is detect multiple an object from the live camera in Jetson TX1.

1. Navigate to detection folder by executing the following command:

    ```
    cd ~/detection
    ```

2. Run webCamDetect.py file by executing the following command:

    ```
    ./webCamDetect.py
    ```
    This will opens up the live camera in Jetson TX1.

3. Hold up a bottle in front of the TX1 camera and look for rectangle on screen and LED0 lighting up.

     ![Bottle Detection](/tx1_labs/images/bottleDetection.png)

4. Modify code to change which LEDs light up based on number of bottles.

    The below figure shows our modified **toggleLEDS** method that turns on LEDs based on the number of detected objects. 
    The logic turns one LED when one object is detected, turns two when two objects are detected and so on.

  ![Multiple Bottle Detection](/tx1_labs/images/multipleObjectsLEDS_lab5.png)




Optional step: If really ambitious, can changed LED algorithm based on size of bounding box
