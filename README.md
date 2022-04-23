# CS5260

There are mainly two ways to execute FL_Robust.ipynb and FGSM.ipynb

1. Upload FL_Robust.ipynb,fl_defence,FGSM.ipynb and fgsm to google drive.
  - Set the variable runFromScratch at the top of the notebook to False
  - Run the notebook
  
2. Upload FL_Robust.ipynb and FGSM.ipynb directly to google collab without fl_defence and fgsm.
  - Set runFromScratch to True
  - Run the notebook

The first method would allow faster execution as all the end result, for example, model parameters, perturbated data etc. are in the uploaded folders, a retrieve action would be enough to get all the data we need.

However, although not recommended, one can actually run the entire notebook by itself without any data using method no.2 . This would automatically create necessary folders and data or save models after training etc. However, these actions are extremely time and resource consuming, especially the evolution differential algorithm, it would take days or even weeks before the entire notebook can finish executing all the cells. Nonetheless, if one would like to experience first hand details, method 2 is there for this purpose.
