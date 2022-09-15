# Location-based-Satellite-to-Map-Convertor-Using-GAN


Converting Satellite Images of given location to Map Using GAN


Several satellites are orbiting the planet so there is a huge collection of satellite images available. Digital Maps have become an integral part of most of our day-to-day lives, especially for navigation. Hence, utilizing satellite images and converting them to maps is of utmost importance.


Description

A Generative Adversarial Network was trained to convert Satellite Images to maps. The input images have been resized to 256X256 and scaled to [-1,1]. 
The program accepts a location as the input and generates the corresponding satellite image which is then converted to maps using the GAN network. 

Dataset

The map dataset which has the satellite images and their respective map image has been used for training. The training set consists of 1096 images.
Link to the dataset : [http://efrosgans.eecs.berkeley.edu/pix2pix/datasets/maps.tar.gz]


Output and Results

Sample output is shown below which was obtained after training the model for 300 epochs:

<img width="450" alt="Screen Shot 2022-09-14 at 9 03 40 PM" src="https://user-images.githubusercontent.com/40431641/190315430-ccc37f1c-4060-4c27-ae07-fdce742b8f76.png">
