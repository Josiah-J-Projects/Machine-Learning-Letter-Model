# AI Letter Recognizer

## Overview

This project was built on the [notMNIST dataset](http://yaroslavvb.blogspot.com/2011/09/notmnist-dataset.html).

The model was built and trained in Python using TensorFlow and Keras, then converted to TensorFlow.js for browser deployment.

**Training Details**
| | Accuracy |
|---|---|
| Training | 98.9% |
| Test | 95.3% |


## How To Use

### Live Demo (No Setup Required)
Visit **[josiah-j-projects.github.io/Machine-Learning-Letter-Model](https://josiah-j-projects.github.io/Machine-Learning-Letter-Model/)**, draw any letter between A and J on the canvas, and click **Guess Letter**.

- Click **"See what the AI sees"** to view the 28×28 preprocessed image the model actually receives as input
- The **Top 3 Guesses** are shown as confidence bars in the AI view
- Click **Clear** to reset the canvas and draw again

> **Note:** The model only recognises letters A through J. Drawing other letters or symbols will return an unreliable result.

## Tech Stack

| Area | Tools |
|---|---|
| Model Training | Python, TensorFlow, Keras |
| Browser Deployment | TensorFlow.js |
| Frontend | HTML, CSS, JavaScript |
| Dataset | notMNIST (A–J) |
