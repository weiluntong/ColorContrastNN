This project was bootstrapped with [Poetry](https://github.com/python-poetry/poetry).

## Introduction

This project is my next step to creating a more reasonable and useful neural network. YouTuber [`Jabrils`](https://www.youtube.com/channel/UCQALLeQPoZdZC4JNUboVEUg) describes, "... a simple feedforward neural network example..." which he recommends as a good first neural network to start learning about machine learning. That video can be found [here](https://www.youtube.com/watch?v=I74ymkoNTnw). The neural network itself attempts to classify whether white text or black text is better given an arbitrary background color.

## Getting Started

To get started, ensure Python 3.7 and Poetry are installed. After:

### Clone the Repository

This project does not have a production build. Obtain the source by cloning or downloading the repository. If you have git installed, run the following command:

`git clone https://github.com/weiluntong/ColorContrastNN.git`

Otherwise, there is a green button at the top right that says "Clone or download" to obtain the source code.

### Navigate to the source directory

If you cloned the source code, simply `cd` into the directory you just cloned. If you downloaded the zip, you'll have to uncompress it first and then navigate to the directory in a terminal.

### Install dependencies

Run this command:

`poetry install`

and that's it. You're ready to run any of the available scripts.

## Available Scripts

In the project directory, you can run:

### `poetry run start`

Runs the app. You can modify the python files within the `intronn` directory to see different outputs at different stages.

## Learn More

You can learn more in the [Poetry documentation](https://python-poetry.org/docs/).

Python documentation can be found [here](https://docs.python.org/), and PyTorch documentation is [here](https://pytorch.org/docs/stable/).
