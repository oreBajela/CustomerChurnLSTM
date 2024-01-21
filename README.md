# CustomerChurnLSTM
Customer Churn Prediction Using Long Short-Term Memory (LSTM) neural network model
This project, implemented in a Jupyter Notebook, encompasses a machine learning model designed for Customer Churn Prediction utilizing LSTM (Long Short-Term Memory). Its primary objective is to forecast whether a customer will transition between telecommunications service providers, commonly referred to as "churning." The precision of churn prediction holds significant importance for businesses, contributing to the maintenance of customer satisfaction, customer retention, and the mitigation of revenue loss.
The training dataset comprises 4250 samples, where each sample is characterized by 19 features and a boolean target variable, denoted as "churn," indicating the likelihood of a customer churning. The LSTM model was able to make accurate predictions 96% of the time.

# Technologies used 
In this project, several technologies are employed to facilitate the development and execution of the Customer Churn Prediction Using LSTM. Here is a list of the key technologies, along with brief explanations of their purposes in the project:

Python:
Purpose: Python serves as the primary programming language for this project due to its versatility, extensive libraries, and ease of use. It provides a robust foundation for machine learning tasks and data analysis.
Jupyter Notebook:
Purpose: Jupyter Notebook is utilized as the development environment for this project. Its interactive and notebook-based structure allows for a step-by-step execution of code, making it well-suited for exploratory data analysis and model development.
LSTM (Long Short-Term Memory):
Purpose: LSTM is a type of recurrent neural network (RNN) architecture specifically chosen for its ability to capture long-term dependencies in sequential data. In this project, LSTM is employed for its effectiveness in handling temporal patterns, crucial for predicting customer churn based on historical data.

# Software requirements
Here is a list of software requirements along with instructions on how to install them using Python's package manager, or your terminal, pip. Note that some libraries may have specific dependencies that need to be installed separately.
NumPy and Pandas:
pip install numpy pandas

Collections, tqdm, Matplotlib, Seaborn, SciPy:
pip install tqdm matplotlib seaborn scipy

Category Encoders:
pip install category_encoders

Scikit-Learn:
pip install scikit-learn

Graphviz (for Decision Tree Visualization):
Installation:
On Windows: Download and install from Graphviz website
On Linux: Use the package manager (e.g., apt-get install graphviz)
On macOS: Use Homebrew (brew install graphviz)

Additionally, install the Python package:
pip install graphviz

TensorFlow (for Neural Networks):
pip install tensorflow

YData Profiling:
pip install ydata-profiling

Keras:
pip install keras

IPython, six:
pip install ipython six

ProfileReport, EarlyStopping, ReduceLROnPlateau, permutation_importance, Balanced Accuracy Score (specific to Scikit-Learn version):
pip install ydata-profiling

Matplotlib Configuration (optional, for custom styling):
This does not require installation but is included in the code for custom styling.

# Usage Instructions
Follow these steps to effectively use the Customer Churn Prediction Using LSTM project:

1. Clone the Repository
   Write this in your terminal:
   git clone https://github.com/oreBajela/CustomerChurnLSTM.git

2. Navigate to the Project Directory:
   Write this in your terminal:
   CustomerChurnLSTM

3. Install Dependencies:
Ensure that you have Python installed. Create and activate a virtual environment if needed. Then, install the required dependencies using:
pip install -r requirements.txt

4. Open the Jupyter Notebook:
Launch Jupyter Notebook to interactively run the machine learning model:
jupyter notebook

5. Run the Notebook:
Open the notebook titled Customer_Churn_Prediction.ipynb and execute the cells step by step. This notebook guides you through data preprocessing, model training, and evaluation.

6. Explore Custom Styling (Optional):
The project includes custom styling for visualizations. Feel free to explore or customize the Matplotlib configuration in the notebook if desired.

7. Interpret Results:
After running the notebook, review the results and insights obtained from the Customer Churn Prediction model. Evaluate the performance metrics and visualize key aspects of the analysis.


# Contributing

I welcome contributions to enhance and improve this project. Follow these guidelines to contribute:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Make your changes and commit them: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.
