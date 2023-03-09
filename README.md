# stack_exchange
Extraction of data from xml file format. using ElementTree to sparse. 
storing of data into csv file 
Cleaning of data removal of tags http files and special characters from the data.
counting length of each title and body row storing in new column as body_len and title_len respectively
converting of columns into caterogical bin of range sorting data as good low and very low doing label encoding of particular data.
doing EDA on data.

Post-analysis Questions:
1. Clearly mention and explain the preprocessing phase. Why did you choose a
particular pre-processing step?
using data str function in order to pass trhough each character performing particular methods in order to clean data using regex function for removing http tags 
2.Explain your choice of model and why do you think it performs well?
being a classification problem and to predict it being good low or very low kind of data finding out co-orelation between each columns predecting output.
