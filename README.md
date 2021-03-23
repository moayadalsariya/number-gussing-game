# Number Guessing Game

Basic AI guessing game with OpenCV and Keras

## Demo
![](./images/demo.gif)

## Technology Used in Project 

* Python3
* OpenCV
* Keras
* Tensorflow
* CNN image classification 

## Requirements
* Python3
* Anaconda3
* Webcam


## Set up instructions

Clone the project using git clone

```bash
git clone https://github.com/moayadalsariya/number-gussing-game
```
Then cd to number-gussing-game

```bash
cd number-gussing-game
```
Use the package manager [pip](https://pip.pypa.io/en/stable/) to install requirements dependency

```bash
pip install -r requirements.txt
```
Start Anaconda jupyter notebook

```bash
conda activate base
```
```bash
jupyter notebook
```
New tap will open in your broswer http://localhost:8888/

## How to run the programm

### Collecting images

* open the collect-data.ipynb file and run all the cells (make sure the webcam installed in your system)
* Start collect data, press '1' key in your keyboard in catpure 1 sign (make sure there is white background before collecting images)
* then start collecting next sign '2' by pressing 2 in your keyboard and so on up to number 5
* press 'n' in your keyboard to capture the white background images
* I recommend to capture 100 images per class

### Train the model
* After collecting images, now start train model by opening 'train-model.ipynb' file and run all cells to train model 

### Predict model
* After train model, now we can start the game by run all cells in your Jupyter notebook

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
