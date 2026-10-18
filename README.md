# Movie Genre Classification 🎬

**CodSoft Machine Learning Internship — Task 1**

## Project Overview
This project predicts a movie's genre using its title and plot description with Machine Learning and Natural Language Processing (NLP).

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- Scikit-learn
- TF-IDF Vectorization
- Linear Support Vector Classification (LinearSVC)
- Matplotlib and Seaborn

## Dataset
The dataset contains movie titles, plot descriptions, and genre labels. The model is trained using the training dataset and evaluated using a separate test dataset with actual genre labels.

## Methodology
1. Load and inspect the dataset.
2. Clean missing and duplicate records.
3. Combine movie titles and descriptions.
4. Convert text into numerical features using TF-IDF.
5. Train a LinearSVC classification model.
6. Evaluate the model using accuracy, precision, recall, F1-score, and a confusion matrix.
7. Predict genres for new movie descriptions.

## Results
- **Test Accuracy:** 57.01%
- **Weighted F1-score:** 0.57
- **Macro F1-score:** 0.39

These are the results from the current experiment.

## How to Run
1. Install Python and Jupyter Notebook.
2. Install the required libraries.
3. Place the dataset files in the appropriate folder.
4. Open `Movie_Genre_Classification.ipynb`.
5. Run the notebook cells in order.

## Internship
Developed as part of the CodSoft Machine Learning Internship, Task 1.

## Author
Asif Karim
