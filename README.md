# SpamTweetsClassification

# Project Title
Spam Tweets Classifier / A Machine Learning Template for Binary Classification of Arabic Spam Tweets

# Project Overview

The project title is "Spam Tweets Classifier / A Machine Learning Template for Binary Classification of Arabic Spam Tweets". This is the code used in the article entitled "Arabic spam tweets classification using deep learning" (https://link.springer.com/article/10.1007/s00521-023-08614-w). The dataset is here: https://data.mendeley.com/datasets/86x733xkb8/1
## Project Installation and Setup
This guide will walk you through the installation and setup process for the project, which focuses on binary classification of spam tweets from an Arabic dataset using classical machine learning algorithms and deep learning approaches.

__Prerequisites__  
Before getting started, ensure that you have the following dependencies installed:  

Python 3.x  
pip package manager  

__Dependencies__  
The project requires the following libraries to be installed:  

Keras  
NumPy  
NLTK  
tqdm  
scikit-learn  
TensorFlow  

To install the dependencies, run the following command:  
_pip install keras numpy nltk tqdm sklearn tensorflow_  

Additionally, you will need to download the Arabic word embeddings file for FastText.   
Please follow these steps:  
Download the word embeddings file by clicking [here](https://dl.fbaipublicfiles.com/fasttext/vectors-wiki/wiki.ar.zip).  
Extract the contents of the downloaded zip file.  

__Installation Steps__  
Follow the steps below to install and set up the project:  

Clone the repository from GitHub:  
_git clone https://github.com/your-username/your-project.git_  
  
Navigate to the project directory:  
_cd your-project_  
  
Create a virtual environment (optional but recommended):  
_python -m venv env_  
  
Activate the virtual environment:  
For Windows: _env\Scripts\activate_  
  
For macOS and Linux: _source env/bin/activate_  

Move the downloaded FastText word embeddings file (wiki.ar.vec) to the project directory.

## Usage

Run the main script to start the binary classification of spam tweets:
_python main.py_

## Configuration

No specific configuration is required for this project.

## Contributing

We welcome contributions from the community! To contribute to this project, please follow the guidelines below:

- Fork the repository and create your branch.
- Make your changes and test them thoroughly.
- Submit a pull request clearly explaining the changes you've made.

Please adhere to our code style conventions and ensure your code is well-documented.

## License

This project is licensed under the Apache License 2.0. For more details, see the [License](https://github.com/sanaakaddoura1/SpamTweetsClassification/blob/main/LICENSE) file.

## Support and Contact

If you have any questions, issues, or suggestions, please feel free to open an issue at (https://github.com/sanaakaddoura1/SpamTweetsClassification/issues) or contact us at sanaa.kaddoura@zu.ac.ae  

## Acknowledgements

We would like to acknowledge the following individuals/projects for their contributions or inspiration:

•	Asma AlNashash, Department of Data Science, King Hussein School of Computing Sciences, Princess Sumaya University for Technology, Amman, Jordan  
•	Safaa Henno, Zayed University, UAE  
•	Maher Itani, Computing Department, Academic Development Division, Sabis Educational Services, Choueifat, Lebanon  
•	Suja A. Alex, Department of Information Technology, St. Xavier's Catholic, College of Engineering, Nagercoil, India  
•	D. Jude Hemanth, Department of ECE, Karunya Institute of Technology and Sciences, Coimbatore, India

