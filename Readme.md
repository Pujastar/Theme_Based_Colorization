#Theme Based Colorization

Prerequisites
1. Python (Anaconda) 3.5.4
2. Tensorflow 1.4.0
3. Numpy 1.13.3
4. PIL 4.2.1
5. Matplotlib 2.0.2

Steps to prepare
1. Download the zip and extract it.
2. We have below given folders in it.
a. Checkpoints : contains checkpoint which will saved once a model for given style
image is trained
b. Images : Contains content images
c. Output images : Contains output images when code is saved.
d. Style images : Contains style images
e. Static : Contains images required for website to run
f. Test images : Contains test images for each iteration as given in command.
3. Upload the “deep_learning_project” folder in your google drive.
4. The VGG19 model can be downloaded by running this in the terminal Or from the link :
wget http://www.vlfeat.org/matconvnet/models/beta16/imagenet-vgg-verydeep-19.mat
5. Upload the vgg19 model file in the project folder

Steps to run
1. Training and testing
We first need to train the model
a. Run the “Testing and training.ipynb” file in Google Collab.
b. While running the cells in the file read the instructions given above them.
2. Evaluation
Once training and testing is done and checkpoints are saved we can just use those
checkpoints to run the code.
a. Run the “Evaluate.ipynb”file in Google Collab.
b. While running the cells in the file read the instructions given above them
