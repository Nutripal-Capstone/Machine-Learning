# Machine-Learning
The code is written in Python and aims to classify meal types and provide food recommendations based on maximum nutrient values per day. The code utilizes the TensorFlow library for machine learning tasks.
## Prerequisites
Before running the code, make sure you have the following libraries installed:
1. pandas: for data manipulation and preprocessing
2. numpy: for numerical operations
3. sklearn: for train-test split and data normalization
4. tensorflow: for building and training the machine learning model
## Dataset
[Nutripal Dataset](https://drive.google.com/drive/folders/18NSZ5EwQbRM7VfYQ5K2RjThkROuAQDne?usp=share_link)
## Resource
[FatSecret API](https://platform.fatsecret.com/api/default.aspx?screen=rapih)
## Colab Research Notebook
[Model Build Notebook](https://colab.research.google.com/drive/1QEBz1guDqwruKPgMtQHZAg2_aIgLcMdM?usp=sharing)
## Code Workflow
1. Mount Google Drive
2. Load and preprocess the dataset
3. Calculate calories per unit and normalize serving amount
4. Adjust calories based on normalized serving amount and determine meal types
5. Split data into features and labels
6. Split data into train and test sets and normalize the data
7. Convert labels to one-hot encoding
8. Define and compile the model
9. Train the model
10. Evaluate the model
11. Get user input for maximum nutrient values per day
12. Normalize user input
13. Get meal recommendations
## References 
[Tensorflow](https://www.tensorflow.org)
