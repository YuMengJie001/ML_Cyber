# ML_Cyber
this is for my lab3 project.

How to run this project?

The mian code is 'lab3.ipynb'(actually, it is also the only code file), you should download it and run it at jupyter.

First, we need prepare data.
The data that we need must named like this:

    valid.h5 // this is clean validation data used to design the defense
    test.h5  // this is clean test data used to evaluate the BadNet
    bd_valid.h5 // this is sunglasses poisoned validation data
    bd_test.h5  // this is sunglasses poisoned test data
    bd_net.h5//model
    bd_weights.h5// model
  
and I also recommand you Store these folders in one same folder, and don't use subfolder.

second, if you want to run the "lab3.ipynb", you need Notice two part of my code, Of course, these modifications are very simple.
1. you need to change the  variable 'filePath' according your actual situation， you need change this variable to the file path of data and model, for example if you store the data and model in "C:\Users\Desktop\MLforCyber\lab3", then you need change the 'filePath' to  "C:/Users/Desktop/MLforCyber/lab3/". 
 
   ps:you need noticed that the 'filePath' ends with'/', don't forget to add this '/'.

3. During the code running process, three models(model_X=2.h5,model_X=4.h5,model_X=10.h5)  will be generated, which will be used in our code later. So after generating the models, download these models from Jupyter to your local folder. This folder should be consistent with 'filePath'.In other word, you need to use the folder where you saved the data and the initial model to store these models.(Of course, if you have already downloaded models I uploaded, you don't need to worry about these, just run the code directly)


finally, you do all the thing , just run the code, and waiting for the result
