# Lab 6

The purpose of this lab is how to use TensorRT for Better Performance

1. Change to ~/detection/jetson-inference/data/networks

    ```
    mkdir bottlenet; cd bottlenet
    ```

2. Extract bottlenet: 

    ```
    tar xzf ~/bottlenet.tgz
    ```

3. Remove the Python layer: 

    ```
    patch -p0 < ../../../../deploy_bottlenet.patch
    ```

4. If you want to see what the patch did: 

    ```
    cat ../../../../deploy_bottlenet.patch
    ```

    The below figure shows the full commands for this lab to patch an existing trained model.

    ![Lab 6-1](/tx1_labs/images/lab6a.png)


5. Change to ~/detection/jetson-inference/build/aarch64/bin

    ```
    ./detectnet-camera bottlenet
    ```

6. Notice the 5x speedup in performance!

7. Modify '~/detection/jetson-inference/detectnet-camera/detectnet-camera.cpp' file.

8. Change LED algorithm as previous tasks

9. Go to ~/detectnet/jetson-inference/build and type make to re-compile

