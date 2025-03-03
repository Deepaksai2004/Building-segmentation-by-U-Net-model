# Building-segmentation-by-U-Net-model

I have implemented a u-net model for building segmentation and trained it.. The model is performing well, and I have obtained good results on the test images.. 

# Dataset
The Massachusetts Buildings Dataset consists of 151 aerial images of the Boston area, with each of the images being 1500 × 1500 pixels for an area of 2.25 square kilometers. Hence, the entire dataset covers roughly 340 square kilometers. The data is split into a training set of 137 images, a test set of 10 images and a validation set of 4 images. The target maps were obtained by rasterizing building footprints obtained from the OpenStreetMap project. The data was restricted to regions with an average omission noise level of roughly 5% or less. The large amount of high quality building footprint data was possible to collect because the City of Boston contributed building footprints for the entire city to the OpenStreetMap project. The dataset covers mostly urban and suburban areas and buildings of all sizes, including individual houses and garages, are included in the labels. The datasets make use of imagery released by the state of Massachusetts. All imagery is rescaled to a resolution of 1 pixel per square meter. The target maps for the dataset were generated using data from the OpenStreetMap project. Target maps for the test and validation portions of the dataset were hand-corrected to make the evaluations more accurate.

Link:- https://www.kaggle.com/datasets/balraj98/massachusetts-buildings-dataset
