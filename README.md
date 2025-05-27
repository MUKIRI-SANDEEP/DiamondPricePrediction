# Diamond Price Prediction

## Overview
This project predicts the price of diamonds using machine learning. I used a dataset of diamonds to train a model that can estimate how much a diamond is worth based on its features like **carat, cut, color, and clarity**. This project helped me practice my data analytics skills, which I'm learning to get a job in data science or data analytics.

## Files
* **`diamonds.csv`**: The dataset I used for this project. It has information about diamonds, like their carat weight, cut, color, clarity, and price.
* **`project_diamonds.ipynb`**: My Jupyter Notebook with all the code. It includes loading the data, cleaning it, visualizing it, and training a machine learning model to predict prices.
* **`depth_table.png`**: A picture showing the depth and table proportions of a diamond, which are important for its quality and price.
* **`gia_report.jpg`**: A sample GIA report for a diamond, showing its official grading details.
* **`proportions.png`**: A picture of diamond proportions, explaining how the shape of a diamond affects its value.

## Skills Used
* **Python**: I used Python to write the code for this project.
* **Pandas**: For loading and cleaning the dataset.
* **Scikit-learn**: For training a machine learning model to predict diamond prices.
* **Data Visualization**: I made charts to understand the data better (using Matplotlib).
* **Data Analysis**: I analyzed the diamond features to see what affects the price the most.

## How to Run This Project

1.  **Open the Notebook**:
    * You can open `project_diamonds.ipynb` in Google Colab or Jupyter Notebook.
    * **In Google Colab**: Go to `colab.research.google.com`, click "GitHub," and enter this repository's URL: `https://github.com/MUKIRI-SANDEEP/DiamondPricePrediction`. Then select `project_diamonds.ipynb`.
    * **In Jupyter Notebook (Locally)**: Download both `project_diamonds.ipynb` and `diamonds.csv` and keep them in the same folder.

2.  **Load the Dataset**:
    * The notebook uses `diamonds.csv`.
    * **In Google Colab**: Load it with this code:
        ```python
        import pandas as pd
        df = pd.read_csv('[https://raw.githubusercontent.com/MUKIRI-SANDEEP/DiamondPricePrediction/main/diamonds.csv](https://raw.githubusercontent.com/MUKIRI-SANDEEP/DiamondPricePrediction/main/diamonds.csv)')
        ```
    * **In Jupyter Notebook (Locally)**: If you've downloaded the file to the same folder, use this code:
        ```python
        import pandas as pd
        df = pd.read_csv('diamonds.csv')
        ```

3.  **Run the Code**:
    * Run the cells in the notebook to see the data analysis and price predictions. You'll see steps like loading the data, cleaning it, making charts, and predicting prices with a machine learning model.

## Why I Did This Project
I'm learning data analytics to get a job, and this project helped me practice working with real data and building a machine learning model. It also shows my skills in Python, Pandas, and Scikit-learn, which I've been studying to start my career.
