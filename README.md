# detecting-handwritten-numbers

Implement KNN to detect handwritten images of numbers.

KNN is a machine learning algorithm used for various classification problems. It works by comparing each sample to all other samples in the dataset and performs a voting based on the K closest neighbors.

The dataset we are using contains handwritten images of digits from 0-9. The size of each image is 28 pixels x 28 pixels. Each row is a separate sample. The first value indicates the ground-truth label (which digit the image represents) and the following values are the pixel values of the time.

We will also be implementing PCA in order to reduce the dimensionality of our samples and to improve computation times.

## Requirements

The following Python packages were used in this project
`NumPy, tqdm, and matplotlib,`

## How to run

In this project we will be using Anaconda as our virtual environment manager.

```bash
conda create --name <env name>
```

```bash
conda install --name <env name> numpy
conda install --name <env name> tqdm
conda install --name <env name> matplotlib
```

```bash
source activate <env name>
```

```bash
jupyter notebook
```

Or you can open the notebook in VS code and select the newly created virtual environment as the kernal and run the notebook.****

## Acknowledgements

Professor Ziwei Zhu
