# Crop Recommendation System Using Machine Learning

## Description
The Crop Recommendation System is a machine learning-based application that provides recommendations for suitable crops based on various environmental and soil conditions. It aims to assist farmers and agricultural professionals in making informed decisions about crop selection, optimizing yields, and maximizing profitability.

The system takes into account several factors such as soil type, climate, rainfall, temperature, humidity, and pH levels to determine the most suitable crops for a given region. By analyzing historical data and using predictive models, the system provides personalized recommendations tailored to the specific conditions of a farm or agricultural area.

## Key Features
- **Input Data Collection**: The system allows users to input relevant data such as soil parameters, climate information, and geographic location.
- **Data Preprocessing**: The input data is preprocessed to handle missing values, normalize or scale features, and transform categorical variables.
- **Machine Learning Models**: Various machine learning algorithms are employed, including decision trees, random forests, and logistic regression to build predictive models.
- **Model Training and Evaluation**: The models are trained on historical data and evaluated using appropriate performance metrics to ensure accuracy and reliability.
- **Crop Recommendation**: Based on the trained models, the system recommends the most suitable crops for the given input parameters.

## Technologies Used
- **Python**: Programming language used for model development, data preprocessing, and web application development.
- **Scikit-learn**: Machine learning library used for model training, evaluation, and prediction.
- **Pandas**: Data manipulation library used for data preprocessing and analysis.
- **NumPy**: Library for numerical computing used for handling arrays and mathematical operations.
- **Seaborn and Matplotlib**: Libraries for data visualization and advanced chart building.

## Dataset
The dataset used for this project can be found [here](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset).

## Installation
1. Clone the repository:
    ```sh
    git clone <repository-url>
    ```
2. Navigate to the project directory:
    ```sh
    cd <project-directory>
    ```
3. Create a virtual environment:
    ```sh
    python -m venv venv
    ```
4. Activate the virtual environment:
    - On Windows:
        ```sh
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```sh
        source venv/bin/activate
        ```
5. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
1. Run the Jupyter Notebook:
    ```sh
    jupyter notebook crop_recommendation_system.ipynb
    ```
2. Follow the instructions in the notebook to preprocess the data, train the models, and get crop recommendations.

## Authors
- Devanshu Sawarkar
- Pratham Agrawal
- Devansh Motghare