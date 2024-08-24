# LearnLab_OCR

Material to teach basic OCR concepts


## Getting Started

### Environment set-up

#### 1. Install Anaconda (or Miniconda)
First, you'll need to install Conda to manage your Python environment.

- **Download Anaconda**: [Anaconda Download](https://www.anaconda.com/products/distribution)
- **Or Download Miniconda** (lighter version): [Miniconda Download](https://docs.conda.io/en/latest/miniconda.html)

Follow the installation instructions on the website for your operating system.

### 2. Clone the Repository
Once you have Conda installed, clone this repository to your local machine. Open a terminal and type the following command:

```bash
git clone https://github.com/MarieLynneBlock/LearnLab_OCR.git
cd LearnLab_OCR
```

### 3. Create a Conda Environment
Create a Conda environment for the LearnLab_OCR tutorial notebooks. This will ensure you have all the necessary packages installed without affecting your system Python setup.


1. Open your terminal (or Anaconda Prompt on Windows).
2. Create a new environment named `learnlab-ocr` by running:

```bash
conda create --name learnlab-ocr python=3.11.8
```

3. Activate your environment:

```bash
conda activate learnlab-ocr
```

### 4. Install Required Packages
Inside your activated environment, install the packages required for this tutorial by running:
TODO: add environment.yaml

```bash
conda install jupyter ipykernel
```

This installs Jupyter Notebooks along with the essential libraries for OCR.

### 5. Set Up the Jupyter Kernel
Next, we’ll create a Jupyter kernel so you can use your newly created environment in Jupyter Notebooks.

Run the following command to set up the kernel:

```bash
python -m ipykernel install --user --name learnlab-ocr
```

This will allow you to select the **learlab-ocr** kernel when opening a notebook.

You can check if the kernel is available to be selected, you can run:
```bash
jupyter kernelspec list
```

### 6. Launch Jupyter Notebook
To start Jupyter Notebook, use this command in your terminal:

```bash
jupyter notebook
```

This will open Jupyter in your browser. Navigate to the folder where you cloned the **LearnLab_OCR** repository, and you’ll see the notebook files.

### 7. Select the LearnLab OCR Kernel
When you open a notebook, make sure you’re using the correct environment:

1. Click on the **Kernel** tab at the top.
2. Select **Change Kernel**.
3. Choose **learnlab-ocr** from the list.

You are now ready to start working through the material!
