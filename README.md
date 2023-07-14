# Boosting Ensembles and Voting Algorithms for Classification

## Abstract

Boosting ensembles are commonly used to enhance the accuracy of classification models by training multiple models sequentially and merging their predictions. However, selecting the best model from the ensemble can be challenging. Voting algorithms are a popular method for selecting the best-fit model by aggregating the predictions of multiple models. However, existing voting algorithms have limitations, including hard voting being sensitive to class imbalance and soft voting assuming that all models are equally reliable. Weighted voting is also challenging, requiring expert knowledge and experience to assign weights to models. Despite the acknowledged limitations of traditional voting algorithms, they remain widely used in ensemble methods due to their simplicity and ease of implementation. Moreover, they serve as a baseline for comparison against alternative voting approaches.

In this project, four boosting ensembles are trained using SVM, CART, Decision Trees, and Naive Bayes algorithms as base classifiers. Subsequently, various voting algorithms such as hard voting, soft voting, weighted voting, and others are applied to these four ensembles. The performance of the ensembles is evaluated using accuracy, precision, f1-score recall and confusion matrix as the performance evaluation metric.

The dataset used in this project is collected from two bamboo-dominated districts named Dima Hasao and Karbi Anglong, with one district serving as the training site and the other as the testing site in Assam state.

## Installation

1. Clone the repository or download the project files.
2. Ensure that Python and the necessary dependencies are installed.
3. Open the terminal or command prompt and navigate to the project directory.

   
## Usage

1. Make sure you have the dataset files available in the project directory.
2. Open the desired Python IDE or the terminal/command prompt.
3. Run the main script to train the boosting ensembles and apply the voting algorithms
4. The script will output the results, including the accuracy of each ensemble using different voting algorithms.
5. To know exactly how predict_dataset works, upload a dataset containing a few tuples. The output will indicate whether the location coordinates in each tuple correspond to areas dominated by bamboo, mixed bamboo, pure bamboo, water, barren land, or forest.

Feel free to learn and explore!


