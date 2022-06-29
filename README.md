# NecklineSegmentation

In the Load Data Notebook, the Images are loaded and for some labels are created.

In the Prepare Data Notebook, the data is scaled to the rigth format and data augmentation is performed. The result are a traning data and target data numpy objekts. 

In Train Unet the neural network is trained. The Network is actually not a common UNet, but quite similar. I took the design from a webpage and then modified it to my purposes. At the end of the notebook, the results are visually checked.

