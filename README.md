# Credit-Risk-Modelling

With the use of Machine Learning Algorithms, the implementation of the metioned 3 models of PD, LGD and EAD uses various classifier algorithms for PD such as: Logistic Regression(Binary), Random Forest Classifier, Gradient Boost Classifier and Adaboost along with Logistic and Linear Regression Algorithms for evaluating LGD and EAD models.

# PD Model:
A Probability of Default Model (PD Model) is any formal quantification framework that enables the calculation of a Probability of Default risk measure on the basis of quantitative and qualitative information. Probability of Default Models have particular significance in the context of regulated financial firms as they are used for the calculation of own funds requirements under Basel III regulation. 

# LGD: 
Loss given default (LGD) is the amount of money a bank or other financial institution loses when a borrower defaults on a loan, depicted as a percentage of total exposure at the time of default. A financial institution’s total LGD is calculated after a review of all outstanding loans using cumulative losses and exposure.

# EAD: 
EAD is the predicted amount of loss a bank may be exposed to when a debtor defaults on a loan. Banks often calculate an EAD value for each loan and then use these figures to determine their overall default risk. EAD is a dynamic number that changes as a borrower repays a lender.

# Steps to run it in your local machine:
1. Download the .ipynb files
2. Download the given dataset
3. Upload the .ipynb files to your google drive's folder named "Colab Notebooks"
4. Upload the dataset to your drive
5. Use the command: 
 ```
   from google.colab import drive
   drive.mount('/content/drive/<folder path to your dataset>')
   ```
6. Now you can run the whole python code!
