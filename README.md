# Mushroom Edibility Classification with Random Forest

This project predicts whether a mushroom is edible or poisonous using a Random Forest Classifier. The dataset used is the **Mushroom Classification Dataset** from Kaggle, which includes various features like cap shape, odor, and habitat.

## Dataset

The dataset is sourced from Kaggle and can be downloaded [here](https://www.kaggle.com/datasets/uciml/mushroom-classification).

### Dataset Description

The dataset contains 8,124 rows and 23 columns, where each row represents a mushroom sample. Features include:

- **class**: Edibility of the mushroom (edible or poisonous).
- **cap-shape**: Shape of the mushroom cap.
- **odor**: Smell of the mushroom.
- **gill-color**: Color of the mushroom gills.
- **habitat**: Habitat where the mushroom is commonly found.
- Other categorical features describing the physical and environmental characteristics of mushrooms.

### Dataset Location

- **Data/**: Contains the dataset files downloaded from Kaggle.
- **Notebook/**: Houses the Jupyter notebook for the project.

## Project Structure

The main folders and files in the project are structured as follows:

```plaintext
Mushroom-Classification/
├── Data/
│   └── [dataset files will be here]
├── Notebook/
│   └── [Jupyter notebooks will be here] 
└── README.md
```

## Data Preprocessing
- **Missing Values**: Replaced missing values in the `stalk-root` column with the most frequent value.
- **Encoding**: Used `LabelEncoder` to convert categorical features into numerical values.
- **Splitting**: Divided the dataset into training and testing sets.

## Model Training
A `RandomForestClassifier` was trained on the preprocessed data.


## Model Evaluation
The model achieved the following recall scores:
- **Training Set Recall**: 1.0 
- **Test Set Recall**: 1.0 

## Requirements
To run this project, you'll need the following Python libraries:
- `pandas`
- `scikit-learn`
- `kaggle`
