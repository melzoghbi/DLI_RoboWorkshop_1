# Lab 5
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