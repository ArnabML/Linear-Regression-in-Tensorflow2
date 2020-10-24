# Linear Regression in Tensorflow2
Simple Linear Regression in tensorflow 2.3.0

Steps I followed ->

First I imported all the modules I needed for this and ignored the warnings using import warnings; warnings.filterwarnings('ignore') because I don't have CUDA set up in my windows machine 

The I added the matplotlib inline for the graphs and some simple tasks

After that I made python read the data from the data.csv file using the pandas module

Then I took an overview of the data using the data.head() for reading to first 5 rows of data and python starts counting from 0

After that I made a scatter visualization of the X and y columns and they are our current training data

Then I made a Sequential model using Tensorflow's high level API (application programming interface) of tensorflow and theano

The I got the summary of the model using model.summary()

Now time for the most important step that is training the model
I made a variable called history in which we trained our model inside the variable (a variable in mathemetics is where we store some number and we can also change that later in this case there is data instead of number) our training data is the X and y columns of the data.csv file with 300 epochs for the best training we can even extend it but expanding it with values like 10000, 100000 can give negative results.
There are two things while training they are 1. accuracy 2. loss

So I plotted / graphed the loss of training we got that from the history variable's history attribute so because of that I declared the variable.

So After that I made another column which is not visible in the data.csv file but exists which contains the name of the column is prediction and it contains the prediction data of the X training data column.

So again I made the scatter of the training data but not of the prediction of the training data and the training data is our X and y columns of the data.csv file after that I made another plot inside that plot of the X training data and the prediction of the X training data and our Line and Regression is ready and also implemented in the data and after that I showed that plot and the scatter data is fitted in the evaluation and testing of the model in the real world data and it says that this data is suitable for Linear Regression because the Data is 98% fitted by the Regression Line.

Hope It worked for you If it doesn't work then I recommend to install the latest version of tensorflow (2.3.0) and python 3.6.6 and if it throws error no such file or directory U also need the data.csv file for the code or it can't read the data or else you can contact me on asarkar310@gmail (my gmail).

Have a good Day :D
