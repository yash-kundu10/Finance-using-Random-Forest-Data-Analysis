# Finance-using-Random-Forest-Data-Analysis

1. First we import all the libraries that we use in this project.

2. Then, we load the given data.

3. After that we understand the data using following terms:-

    a) View the raw data with the help of .head() function which shows the first five columns of the data.
   
    b) Dimension of the data with the help of .shape function which gives the no. of columns and rows in the given dataset.
  
    c) Data types of the data with the help of .info() function which gives the whole information of the dataset.
  
    d) Null values of the data with the help of .isnull() function which shows the null value in the given dataset.
  
4. After that we do EDA(Exploratory Data Analysis) which consist the following terms:-

    a) Statistical data analysis with the help of .describe() function which gives count,mean,std,min etc.
 
    b) Response variable analysis which gives the sum of "Fraud" and "Not Fraud".From this we analyse "The majority of the transactions are Not Fraud."
 
    c) Train test split in this before fitting the data into the machine learning model, we should split the data into training data and testing data. This is an important step because         we would like to train the model by fitting the training data. But to test the data, we should use the data that is new to the model. Then only we would be able to calculate the         performance of the model on the unseen data.
  
5. After that we model the data with the help of Random Forest which gives 99.96% accuracy.

6. At last we create the confusion matrix for "Random Forest" model.
