# Spam Email Detection

This project focuses on developing a deep learning model to classify emails as either spam or ham (non-spam). The primary goal is to create a reliable classifier that can help filter out unwanted spam emails while minimizing the misclassification of legitimate messages.

## Installation Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/Luciano-C/Spam-Email-Detection-Tensorflow
cd Spam-Email-Detection-Tensorflow
```

### 2. Create and Activate a Virtual Environment

To avoid any dependency conflicts, it's recommended to use a virtual environment. You can create one using `virtualenv` or Python's built-in `venv`.

#### Using `virtualenv`

```bash
# Install virtualenv if you don't have it
pip install virtualenv

# Create a virtual environment
virtualenv venv

# Activate the virtual environment
# On Windows
venv/Scripts/activate

```

### 3. Install the Dependencies

After activating the virtual environment, install the required dependencies listed in the `requirements.txt` file.

```bash
pip install -r requirements.txt
```

### 4. Download GloVe Embeddings

This project uses GloVe embeddings for natural language processing tasks. Please follow the steps below to download and set them up:

1. Download the [GloVe embeddings](https://nlp.stanford.edu/data/glove.6B.zip).

2. Extract the downloaded zip file.

3. Move the `glove.6B.100d.txt` file to the `data` directory within the project:


### 5. Running the Project

Now you should be ready to run the project. Simply execute the Python script:

```bash
jupyter notebook
```

## Deactivating the Virtual Environment

When you're done working, deactivate the virtual environment with the following command:

```bash
deactivate
```

