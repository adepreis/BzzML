# BzzML

## Dataset

Place image dataset in the `images` folder. <!-- are we allowed to share dataset or should we ask the user to download it by itself ? (requires a Kaggle account) -->

You can find it under _Honey Bee pollen_ [kaggle repository](https://www.kaggle.com/ivanfel/honey-bee-pollen)  published in the framework of the following publication :

<!-- If you publish work based on this dataset, please cite the following publication: -->

> Ivan Rodriguez, Rémi Mégret, Edgar Acuña, José Agosto, Tugrul Giray. Recognition of pollen-bearing bees from Video using Convolutional Neural Network, IEEE Winter Conf. on Applications of Computer Vision, 2018, Lake Tahoe, NV. https://doi.org/10.1109/WACV.2018.00041


## Dataset description

Contains 714 high resolution (180x300) images of individual bees on a ramp (blue background) for pollen bearing and non-pollen bearing honey bees.

![Illustration : application preview](./doc/pollenCaracterization.jpg)

Image's name prefix define their class: NPxxxx-xxx.jpg for non-pollen and Pxxxx-xxx.jpg for pollen bearing bees.

`Read-skimage.ipynb`, `Read.ipynb` and `pollen_data.csv` was included with the dataset too.