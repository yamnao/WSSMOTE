### Watershed-based oversampling for imbalanceddataset classification: WSSMOTE

For several real-world problems, the dataset is composed of two or more imbalanced classes: a minority and majority ones. 
With usual machine learning methods, this imbalance often leads to poor results where the majority class is over-fitted while the minority class is misclassified. 
To alleviate these issues, several pre-processing methods, such as SMOTE andDBSMOTE, create new artificial points for the minority class. 
Nevertheless, these oversampling methods explicitly or implicitly make hypothesesabout the clusters size, shape, or density that may not fit the datasetin  practice.  
We  propose  to  improve  these  oversampling methods and reduce cluster assumptions, by relying on a parameter-freeclassifier:  the  watershed-cut.  
We  called  this  method  WSSMOTE. 
Code and Tab3 are developed in this JupyterLab. 


## Getting Started:

# Prerequises:
Download the Jupyter Lab in your session

For WSSMOTE.ipynb file: 
    1. Open the WSSMOTE.ipynb file
    2. Install higra: pip install higra (or uncomment first cell)
    3. Install smote-variants: pip install smote-variants (or uncomment second cell)
    4. Install imbalanced-learn: pip install -U imbalanced-learn (or uncomment third cell)
    5. Change the path to access to Parameters.xlsx file
    6. Launch file

For WSSMOTE_ChessBoard.ipynb file: 
    1. Open the WSSMOTE_ChessBoard.ipynb file
    2. Install higra: pip install higra (or uncomment first cell)
    3. Install smote-variants: pip install smote-variants (or uncomment second cell)
    4. Launch file
    
# Running:
Run all the WSSMOTE.ipynb file, results will appear at the end in several tabs (each tab represents an oversampling method).

## Authors:
Ouchtar Yamna, Laurent Najmann, Benjamin Perret

