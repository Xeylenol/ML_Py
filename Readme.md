# Machine Learning with Python

This repository contains machine learning implementations in Python, utilizing both Scikit-learn and custom implementations.

## Resources

*   **Simple MNIST Neural Network from Scratch:** [Kaggle Kernel](https://www.kaggle.com/code/wwsalmon/simple-mnist-nn-from-scratch-numpy-no-tf-keras) (Numpy, No TensorFlow/Keras)
*   **YouTube Tutorial:** [Mathematical Optimization](https://www.youtube.com/watch?v=AM6BY4btj-M)
*   **Python for Data Analysis with Projects:** [YouTube Playlist](https://www.youtube.com/playlist?list=PLeo1K3hjS3uvCeTYTeyfe0-rN5r8zn9rw)
*   **Linear Regression with Scikit-learn:** [Jovian Notebook](https://jovian.ai/aakashns/python-sklearn-linear-regression)
*   **Scikit-learn Documentation:** [Official Website](https://scikit-learn.org/stable/)
*   **Pattern Recognition and Machine Learning:** [Bishop Book](Bishop-Pattern-Recognition-and-Machine-Learning)
*   **ChatGPT Prompt Engineering for Developers:** [DeepLearning.AI Short Course](https://www.deeplearning.ai/short-courses/chatgpt-prompt-engineering-for-developers/)

## Implementation Notes

Some implementations leverage the Scikit-learn library, while others are built from scratch using Python.

## Setup

### Environment Setup
To create and set up the Python environment:

```bash
# Create virtual environment
python -m venv ml_env

# Activate the environment
ml_env\Scripts\activate

# Install required packages
pip install pandas numpy scikit-learn matplotlib jupyter word2number

# Install ipykernel for Jupyter notebook support
pip install ipykernel

# Register your environment as a Jupyter kernel
python -m ipykernel install --user --name=ml_env --display-name="ML Environment"

# Create requirements file
pip freeze > requirements.txt
```

### Installing Dependencies
To install from requirements file:

```bash
pip install -r requirements.txt
```

### VS Code Setup
1. Open VS Code in your project directory
2. Press `Ctrl+Shift+P` and select "Python: Select Interpreter"
3. Choose the "ML Environment" kernel for Jupyter notebooks
4. Ensure your virtual environment is activated when working on the project

## Modules 
The following Python modules are required for this project:
- pandas
- numpy
- scikit-learn
- matplotlib
- jupyter
- word2number
- ipykernel