# Predictive Analytics

Predictive analytics is an applied field that uses a variety of quantitative methods that make use of data in order to make predictions

### Categorical variables: 
Variables that can be accepted as values with only a finite number of categories such as gender, country, type of transaction, age group, marital status, movie genre, and so on. Within this type of variables there are two sub-types:
   ####     . Ordinal variables: 
When the categories have some natural ordering: for instance, age groups (21–30, 31–40, 41–50, 51+) or shirt size (small, medium, large)
   ####      . Nominal variables: 
Those categorical variables whose values have no meaningful order

### Numerical variables: 
Variables whose values can vary in some defined interval. There are two sub-types, although the distinction in most cases won't be as important:
   ####      . Continuous variables: 
Those that in principle can take any value within an interval: the height of a person, stock prices, the mass of a star, and credit card balance are examples of continuous variables
   #####     . Integer variables: 
Those that can take only values that are integer numbers: number of children, age (if measured in years), the number of rooms in a house, and so on


## The Predictive Analytics Process
   1. Problem understanding and definition 
   2. Data collection and preparation 
   3. Data understanding using exploratory data analysis (EDA) 
   4. Model building 
   5. Model evaluation 
   6. Communication and/or deployment 

### 1. Problem understanding and definition:
**Goal:** Understand the problem and how the potential solution would look. Also, define the requirements for solving the problem.

This is a key stage because here we establish together with the stakeholders what the objectives of the predictive model are—which is the problem that needs to be solved and how the solution looks from the business perspective. We also establish explicitly the requirements for the project. The requirements should be in terms of **inputs:** what the data needed for producing the solution is, in what format it is needed, how much data is needed, and so on.

### 2. Data collection and preparation:
**Goal:** Get a dataset that is ready for analysis

### 3. Dataset understanding using EDA
**Goal:** Understand your dataset
EDA is a combination of numerical and visualization techniques that allow us to understand different characteristics of our dataset, its variables, and the potential relationship between them.

Now it is time for we to start understanding our dataset by starting to answer questions like the following:
* What types of variables are there in the dataset?
* What do their distributions look like?
* Do we still have missing values?
* Are there redundant variables?
* What are the relationships between the features?
* Do we observe outliers?
* How do the different pairs of features correlate with each other?
* Do these correlations make sense?
* What is the relationship between the features and the target?

All the questions that we try to answer in this phase must be guided by the goal of the project: always keep in mind the problem we are trying to solve. Once we have a good understanding of the data, we will be ready for the next phase: **Model Building**.

### 4. Model Building
**Goal:** Produce some predictive models that solve the problem

We build many predictive models and will then evaluate to pick the best one. We must choose the type of model that will be trained or estimated. The term model training is associated with machine learning and the term estimation is associated with statistics.

### 5. Model Evaluation
**Goal:** Choose the best model among a subset of the most promising ones and determine how good the model is in providing the solution

Usually, one or more main metrics will be used to evaluate how good the model performs. Depending on the project, other criteria may be considered when evaluating the model besides metrics, such as computational considerations, interpretability, user-friendliness, and methodology, among others.

The best model is not the fanciest, the most complex, the most mathematically impressive, the most computationally efficient, or the latest in the research literature: the best model is the one that solves the problem in the best possible way.

### 6. Communication and/or Deployment
**Goal:** Use the predictive model and its results

Finally, the model has been built, tested, and well evaluated: we did it! In the ideal situation, it solves the problem and its performance is great; now it is time to use it. How the model will be used depends on the project; sometimes the results and predictions will be the subject of a report and/or a presentation that will be delivered to key stakeholders, which is what we mean by communication—and, of course, good communication skills are very useful for this purpose.

Sometimes, the model will be incorporated as part of a software application: either web, desktop, mobile, or any other type of technology. In this case, we may need to interact closely with or even be part of the software development team that incorporates the model into the application. There is another possibility: the model itself may become a "data product". For example, a credit scoring application that uses customer data to calculate the chance of the customer defaulting on their credit card.

**Although we have enumerated the stages in order, keep in mind that this is a highly iterative, non-linear process and we will be going back and forth between these stages; the frontiers between adjacent phases are blurry and there is always some overlap between them, so it is not important to place every task under some phase. For instance, when dealing with outliers, is it part of the Data collection and preparation phase or of the Dataset understanding phase? In practice, it doesn't matter, you can place it where you want; what matters is that it needs to be done!**

## CRISP-DM Approach
CRISP-DM (Cross-Industry Standard Process for Data Mining) is another popular framework for doing predictive analytics is the cross-industry standard process for data mining. In this methodology, the process is broken into six major phases. The author (Wirth, R. & Hipp, J. (2000)) clarify that the sequence of the phases is not strict; although the arrows indicate the most frequent relationships between phases, those depend on the particularities of the project or the problem being solved. These are the phases of a predictive analytics project in this methodology:

1. Business understanding
2. Data understanding
3. Data preparation
4. Modeling
5. Evaluation
6. Deployment

## Epicycles of Data Analysis
1. The epicycles are the following:
2. Develop expectations
3. Collect data
4. Match expectations with the data
5. State a question
6. Exploratory data analysis
7. Model building
8. Interpretation
9. Communication

The word **epicycle** is used to communicate the fact that these stages are interconnected and that they form part of a bigger wheel that is the data analysis process.

### Further Reading
* Chin, L., Dutta, Tanmay (2016). NumPy Essentials. Packt Publishing.
* Fuentes, A. (2017). Become a Python Data Analyst. Packt Publishing
* VanderPlas, J. (2016). Python Data Science Handbook: Essential Tools for Working with Data, O'Reilly Media.
* Wirth, R., Hipp, J. (2000). CRISP-DM: Towards a standard process model for data mining. In Proceedings of the 4th international conference on the practical applications of knowledge discovery and data mining.
* Yim, A., Chung, C., Yu. A. (2018) Matplotlib for Python Developers. Packt Publishing.
