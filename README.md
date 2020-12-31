# Generate_Celebrity_Faces
This Notebook will use mnist & CelebFaces Attributes (CelebA) Datasets 
to generate new mnist image & Celebrity Face .<br />
the code may take a lot of time and consume a lot of resources so it better to use cloud services .<br />
helper.py is code that prepare data for you save you alot of time and efforts give you chance to focus on your project.<br />

## Code overview
This code is based on GANS. It contains 2 main functions discriminator and Generator . <br />
### Generator : <br />
The generator part of a GAN learns to create fake data by incorporating feedback from the discriminator.<br /> It learns to make the discriminator classify its output as real.<br />
### Discriminator :<br/>
The discriminator in a GAN is simply a classifier. It tries to distinguish real data from the data created by the generator.<br /> It could use any network architecture appropriate to the type of data it's classifying.
## Built With
1 - [tensorfow-v1](https://www.tensorflow.org/) - The web framework used<br />
2 - [PIL](https://python-pillow.org/) - python image library<br />
3 - [Matplotlib](https://matplotlib.org/) -  Visualization with Python<br />
4 - [Numpy](https://numpy.org/) - The fundamental package for scientific computing with Python<br />

## Authors

Origanally this is a part of Deep_Learning_Nanodegree [Udacity](https://www.udacity.com/course/deep-learning-nanodegree--nd101)

***Ahmed_Hekal***
