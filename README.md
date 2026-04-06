# my-final-project
The dataset contains 5,880 observations and 36 features, where each observation represents a blood cell sample. The target variable used in this project is `anomaly_label`, which classifies cells as normal or abnormal.

## How to Run the Code
To run this project, open the notebook file `final_project_draft.ipynb` in VS Code or Jupyter Notebook.

Make sure the following libraries are installed:
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  

Run each cell in order starting from loading the dataset to the final model comparison.

## Results Summary
Two models were used in this project: Random Forest and Decision Tree. Both models did very well and were able to correctly classify all samples in the dataset. This suggests that the features in the dataset were clearly separated as normal and abnormal cells without error.

Even though Random Forest is a more complex model, the Decision Tree produced the same results. Because of this, the simpler model may be easier to use and understand while still maintaining strong performance.