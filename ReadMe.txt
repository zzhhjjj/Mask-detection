Our project has two parts. 

The first part is to fine tune DenseNet 201 model on the dataset in order to distinguish between 
photos with masks and photos without masks. So it's run on Kaggle. 
https://www.kaggle.com/haojunz/face-mask-detection?scriptVersionId=82370703

Faster RCNN didn't worked well, but I still put the link here.


The second part is run on jupyter notebook. It takes an video and output the annotated video. 
In order to do so, we need the model trained on the first part. The parameters that need to 
be adjusted are putted at the beginning. For a video of 3 seconds, it could take one minute to run.
I have putted a demo to demonstrate our work.

And the last part of this jupyter notebook is independent from the previous codes, it implement an adhoc mask detection run on PC. 
 
