# Can I Better Predict a Transaction's Budget Category Than My Budgeting Software

# Project Background:
I have been using a budgeting tool for almost 9 years to manage all of my financial accounts and budget. Every account I’ve had since 2012 has been connected so it has all of my transactions. The software automatically categorizes your transactions into predetermined budget categories (groceries, shopping, rent, etc).
Presumably, the software uses some type of machine learning algorithm to classify the transaction into a budget category. For the most part it does a decent job but every month there are quite a few transactions that I need to manually change to the correct category. 

# Problem statement:
I think it would be really interesting to attempt to use a DNN to read the text description and attempt to do my own category classification. I could then compare against the software's preassigned data going forward and see whether I can get close to matching it's accuracy.

I ran the notebook in Google Colab with TPUs (Total Runtime: ~10min)
