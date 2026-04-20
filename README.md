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
Two models were used in this project: Decision Tree and Random Forest. After adding engineered features and optimizing both models, the Decision Tree achieved an accuracy of 0.83, while the Random Forest achieved an accuracy of 0.81. These results are more realistic compared to the initial draft, where both models achieved perfect accuracy, indicating that the updated model is learning meaningful patterns rather than memorizing the data.

The results show that features related to cell size, especially cell diameter and nucleus area, play an important role in classification. Visualizations and feature importance analysis confirmed that cell diameter has a stronger relationship with the anomaly label compared to nucleus area alone. This supports the original goal of the project, which was to determine whether these features could help identify abnormal cells.

Overall, the Decision Tree performed slightly better while also being simpler and easier to interpret. Based on these results, the Decision Tree is recommended for this problem because it provides strong performance while making the relationship between features and predictions clearer. The model should be used as a support tool rather than a fully automated system, with human use included for important decisions. This ensures accuracy while still benefiting from the model.