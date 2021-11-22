# Data-Science-Project_Job_Hackthon
Agenda:
• The main objective is to determine whether the employee will leave the company or 
not. We can achieve this by using multiple algorithms/Statistical Techniques. To 
determine whether the employee will leave the company or not, we have to analyse 
the respective predictors or supporting features like Age, City, Salary etc. 
• Pre-requisites and Resources
• Data Collection and Problem Statement
• Exploratory Data Analysis with Pandas and NumPy
• Data Preparation using Sklearn
• Selecting and Training a few Machine Learning Models

Problem Statement:
Predicting Employee Attrition :
In recent years, attention has increasingly been paid to human resources (HR), since worker 
quality and skills represent a growth factor and a real competitive advantage for companies. 
After proving its mettle in sales and marketing, artificial intelligence is also becoming 
central to employee-related decisions within HR management. Organizational growth largely 
depends on staff retention. Losing employees frequently impacts the morale of the 
organization and hiring new employees is more expensive than retaining existing ones.
You are working as a data scientist with HR Department of a large insurance company 
focused on sales team attrition. Insurance sales teams help insurance companies generate 
Jyothi Prakash Kalla 9380611851 kallajyothiprakash@gmail.com
new business by contacting potential customers and selling one or more types of insurance. 
The department generally sees high attrition and thus staffing becomes a crucial aspect.
To aid staffing, you are provided with the monthly information for a segment of 
employees for 2016 and 2017 and tasked to predict whether a current employee will 
be leaving the organization in the upcoming two quarters (01 Jan 2018 - 01 July 
2018) or not, given:
1. Demographics of the employee (city, age, gender etc.)
2. Tenure information (joining date, Last Date)
3. Historical data regarding the performance of the employee (Quarterly rating, 
Monthly business acquired, designation, salary)

AIM:
There are very few people who begin and end their careers in one company. Most 
people move on after a time, or the company forces them to move on with an 
involuntary termination. People leaving organizations seems like a quite 
straightforward matter, but there is a lot to unpack with employee attrition.
Data Pre-processing: 
• In the current dataset, the response variable is not given directly. Instead of that 
they had given the last working date. By using python code we created a new 
variable called ‘Target’ and assigned values by using last working date variable • I 
analysed each feature to know the Insights of that feature. I achieved this by using 
different plots like Histogram, Boxplot, countplot etc • I used the Standard Scaler to 
standardize the numerical features, it transformed the numerical features values 
between the range -1 to 1 • The categorical features are labelled into the numerical 
Jyothi Prakash Kalla 9380611851 kallajyothiprakash@gmail.com
values using Label Encoder • In the current dataset, the values of Target variable 
are unbalanced. To balance the data, we used SMOTE method to balance the data • 
Grouping is performed on Employee id by averaging the Total Business Value as 
there are repeated records with same Employee Id with only Total Business Value 
changing.

Splitting the Data: 
We will split the data into training and testing. Here, we are splitting the train data into 
75% and test data into 25%. We achieved this by using train_test_split in the sklearn 
library.

Statistical Techniques/Algorithms:
• For the current dataset, we used multiple machine learning algorithms like 
DecisionTree Classifier, RandomForest Classifier, etc. • But, svm/Support Vector 
Classifier gives us maximum accuracy(73.07%) with respect to public test data. • So, 
I am using the svm algorithm to predict whether the employee will leave the 
company or not.

Further Improvements: 
We can further improve our model by applying different hyperparameter tuning 
techniques for respective algorithms.
