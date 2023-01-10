
<h1 align="center">
  <br>
  U-net and Facebook MaskFormer for satellital object segmentation
  <br>
</h1>

<h4 align="center">Implementation of advanced neural networks for segment the cover of satellital image maps.</h4>

<p align="center">
  <a href='https://keras.io/' target="_blank"><img alt='keras' src='https://img.shields.io/badge/Keras-100000?style=for-the-badge&logo=keras&logoColor=FFFFFF&labelColor=D10000&color=D10000'/></a> <a href='https://www.tensorflow.org/?hl=es-419' target="_blank"><img alt='tensorflow' src='https://img.shields.io/badge/Tensorflow-100000?style=for-the-badge&logo=tensorflow&logoColor=EC8D1E&labelColor=908B8B&color=E45A27'/></a> <a href='https://www.kaggle.com/' target="_blank"><img alt='kaggle' src='https://img.shields.io/badge/Kaggle-100000?style=for-the-badge&logo=kaggle&logoColor=37BAE8&labelColor=BEFDFF&color=37BAE8'/></a>
</p>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#download">Download</a> •
  <a href="#credits">Credits</a> •
  <a href="#related">Related</a> •
  <a href="#license">License</a>
</p>

![screenshot](https://winter-anchovy-50e.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2Fa52ceed6-f21c-4238-8b4c-5775749e23e0%2Fgg.png?id=cf256619-0ae0-4361-93dd-96210bfc9cb4&table=block&spaceId=12eea25e-0790-4a8f-aa1c-b60f93c02da2&width=2000&userId=&cache=v2)

## Key Features

This deep learning model predicts the class masks into an satellital image. The dataset is taken from the [Deepglove land cover classification Dataset
](https://www.kaggle.com/datasets/balraj98/deepglobe-land-cover-classification-dataset). So here are the key features of this project:

* Model is built using a Unet Neural Network Architecture. We used optimal methods such like
	- **Pooling** 
	- **Dropout** 
	- **BatchNormalization**
	- **Regularizers**
	- **Padding**
* We got a 80.2% of validation accuracy.
* The learning curve shows a small amount of overfit. The graph is the following (The orange one is the accuracy curve and blue is the loss curve)

![screenshot](https://winter-anchovy-50e.notion.site/image/https%3A%2F%2Fs3-us-west-2.amazonaws.com%2Fsecure.notion-static.com%2F55726099-c4b0-4622-9e3a-6c5ea6a39f31%2FUntitled.png?id=e0833681-c4d9-4c28-9a41-2652bbd7a5e8&table=block&spaceId=12eea25e-0790-4a8f-aa1c-b60f93c02da2&width=1190&userId=&cache=v2)

## How To Use

To clone and run this application, you will need [Git](https://git-scm.com).

```bash
# Clone this repository
$ git clone https://github.com/santiagoahl/land-cover-segmentation.git

# Go into the repository
$ cd land-cover-segmentation

# Run
$jupyter notebook
```

## Credits

This model uses the following open source datasets and packages:

- [Keras](https://keras.io/)
- [Tensorflow](https://www.tensorflow.org/?hl=es-419)
- [Land Cover Masks Dataset](https://www.kaggle.com/datasets/balraj98/deepglobe-land-cover-classification-dataset)
- [Pandas](https://pandas.pydata.org/)
- [Numpy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)


## License

MIT

---

> Web Site [santiagoal.super.site](https://santiagoal.super.site/) &nbsp;&middot;&nbsp;
> GitHub [@santiagoahl](https://github.com/santiagoahl) &nbsp;&middot;&nbsp;
> Twitter [@sahumadaloz](https://twitter.com/sahumadaloz)
