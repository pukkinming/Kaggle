This repo has the code for running the [dog breed identification](https://www.kaggle.com/c/dog-breed-identification). I was able to yield a multi-class log loss of 0.01359 and ranking of 104/1286 in the public leaderboard.

The idea is to extract features from pretrained ConvNets including inception and resnet to speed up. Please run the python notebook in sequence to know more.

In case you cannot load the python notebook, I uploaded pdf versions of the notebook.

To run the code, please have the following prerequisites:
- mxnet 1.0.0
- panads 0.21.0
- numpy 1.13.3
- tqdm 4.11.2
