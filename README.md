# PyTorch Learning Projects

A personal project where I explore PyTorch through a collection of small deep learning problems involving tabular data, computer vision, and natural language processing.

The goal is not to build production-ready models or achieve state-of-the-art performance, but to gain practical experience with the PyTorch ecosystem and understand how modern deep learning workflows are structured.

Throughout the project, I use Pandas and Scikit-Learn for preprocessing, PyTorch for model development and training, and Matplotlib for analysis and visualization.

---

## Motivation

After implementing several classical machine learning algorithms from scratch, I wanted to move toward modern deep learning frameworks and understand how neural networks are built and trained in practice.

While frameworks such as PyTorch make model development significantly easier, many important questions still remain:

* How are datasets represented and loaded efficiently?
* How do training and validation loops work?
* What changes when moving from tabular data to images or text?
* How are convolutional neural networks structured?
* What does transfer learning actually involve?
* How are transformer-based language models fine-tuned?

This repository was created to answer those questions through hands-on experimentation.

Rather than focusing on a single large project, I implemented several smaller problems covering different data modalities and modeling approaches.

---

## Implemented Projects

### Tabular Data Classification

A binary classification problem using structured numerical data.

Topics explored:

* Feature preprocessing and normalization
* Train/validation/test splitting
* Tensor datasets and dataloaders
* Fully connected neural networks
* Binary classification losses
* Model evaluation

### Image Classification

A convolutional neural network trained on image data.

Topics explored:

* Image preprocessing
* Data augmentation
* Convolutional layers
* Pooling operations
* CNN architecture design
* Multiclass classification

### Transfer Learning

An image classification project based on a pretrained neural network.

Topics explored:

* Feature extraction
* Fine-tuning pretrained models
* Transfer learning workflows
* Efficient training strategies
* Model adaptation to new tasks

### Text Classification

A natural language processing task using transformer-based models.

Topics explored:

* Text preprocessing
* Tokenization
* Transformer architectures
* Language model fine-tuning
* Binary text classification

---

## PyTorch Concepts Explored

The repository covers many of the fundamental components of modern PyTorch workflows:

* Tensors and tensor operations
* Automatic differentiation
* Neural network modules
* Custom datasets
* Data loaders
* Training loops
* Validation loops
* Loss functions
* Optimizers
* Learning rate scheduling
* GPU acceleration
* Transfer learning
* Transformer models

Perhaps the most valuable lesson was understanding how different data types require different preprocessing techniques and model architectures, while still following the same underlying machine learning workflow.

---

## Experiments

Some of the experiments performed throughout the project include:

* Comparing different neural network architectures
* Monitoring training and validation loss
* Evaluating classification performance
* Investigating overfitting and regularization
* Applying transfer learning to image datasets
* Fine-tuning pretrained transformer models
* Visualizing learning curves and predictions

---

## Technologies

* Python
* PyTorch
* Torchvision
* Transformers
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook

---

## Project Structure

```text
.
├── README.md
├── tabular_data_classification
│   └── 01.ipynb
├── image_classification
│   └── 02.ipynb
├── pretrained_models
│   └── 03.ipynb
├── text_classification
│   └── 04.ipynb
└── datasets/
```

---

## Key Takeaways

This project helped me develop a deeper understanding of:

* The PyTorch programming model
* Neural network training workflows
* Deep learning for structured, visual, and textual data
* Transfer learning techniques
* Transformer-based NLP models
* Data preprocessing pipelines
* Model evaluation and visualization

While the projects are intentionally small, they mirror many of the workflows used in modern deep learning applications and provide practical experience with the tools and abstractions commonly used in industry.
