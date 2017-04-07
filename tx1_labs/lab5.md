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

3. Hold up bottle in front of camera and look for rectangle on screen and LED0 lighting up.

     ![Bottle Detection](/tx1_labs/images/bottleDetection.png)

4. Modify code to change which LEDs light up based on number of bottles.



Optional step: If really ambitious, can changed LED algorithm based on size of bounding box
