# Predicting-Interest-Rates-

Loan Smart is a lending advisory firm. Based on their client’s characteristic and needed loan amount they
advise them on which Financial Institution to apply for loan at. So far their recommendations have been
based hunches business experience. Now they are trying to leverage power of data that they have collected so
far.

They want to check whether given their client’s characteristics , they can predict how much interest rates
they will be offered by various financial institution. They want to run with proof of concept for this idea.
They have given us data collected for one such financial institution.

What we need to do is to figure out whether using that data we can predict interest rate offered to client.  We have been given training data and testing data. Testing data doesnt have response values i.e. Interest Rates. We’ll eventually want to make prediction on this data where the response is unknown. 


We have used data wrangling library 'dplyr' along with a library named 'car for removing multicollinearity or redundant variables as per high VIF values.    
