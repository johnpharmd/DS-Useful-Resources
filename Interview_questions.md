### Week 1.1: 

1. What data would you love to acquire if there were no limitations?
2. What would you do with that data (projects, startups, apps)?
3. Bring something for “Show and Tell” (screenshare) that got you interested in this data or shows why it is interesting to you.

### Week 1.2:

1. Why are you at Lambda School?
2. What did you do before Lambda School?
3. What is something interesting about you?

### Week 2:

1. What is the difference between quantitative and qualitative data? What are a few examples of each?
2. What are numpy and pandas and what are they used for?
3. How might you plot time-series data in a clear way? What would be a bad way to visualize it and why?
4. What is data science to you?
5. What is the most confusing topic from week one of class?

### Week 3:
Biases in data visualization

There are numerous types/forms of biases, such as technical, language bias, biased data narrative, replication bias. Good article here: https://alshams.github.io/responsibledata/bias-in-data-viz/
Can you find an example where the chart or other data visualization is misrepresenting the actual research? 
1. How might a visualization appear different to viewers from different cultures?
2. What are apophenia and confirmation bias and how do they affect the creation of visualizations?
3. At what point could a misleading chart become unethical?

### Week 4:
1. What is the difference between descriptive statistics
  and inferential statistics?
2. How would you explain a 95% confidence interval
  to an executive with no statistics background?
3. What is a t-test?
4. What are some different types of distributions
  and what are their qualities?
5. What are null and alternative hypotheses?
  Give an example.
6. When is more data better? When is it worse?
7. How do you keep up with economic and
  business news? How about data science news?

### Week 7:
1. What does PCA stand for and why is it useful? What preprocessing technique(s) is/are important before performing PCA on a dataset? Why is it important?
* PCA = Principal Component Analysis
* It is a useful dimensionality reduction technique.  PCA figures out the orthogonal dimensions that contribute the most to the variation in your data, essentially giving you a new coordinate axis from which to look at your data. It projects your data on these new, more useful dimensions, each made up of linear combinations of the original coordinates.  PCA tells you how much each dimension contributes to the variance in the data.  Since a few of the new dimensions (the principal components, PCs) usually contribute the most variation, you can decide how many of those to keep and then disregard all the others. If only, say, 5 PCs account for 95% of the variation, you can choose to ignore all other PCs and you have reduced your overall dimensionality to 5 dimensions.
* You want to normalize your data before running PCA (to have a mean of 0 and a standard deviation of 1).  That way dimensions with larger numbers have the same effect on the calculations as dimensions with smaller numbers.

2. What are eigenvalues and eigenvectors?
* Linear transformations consist of just addition and scalar multiplication. They are operations that stretch or rotate the coordinate system.,
* When you apply a linear transformation to a coordinate system, there can exist nonzero vectors (eigenvectors) that change only by a scalar factor (the eigenvector); they can stretch, but they keep their direction. 

3. Describe the process used by the K Means clustering algorithm.
* The number of clusters to use (k) is a given.
* First randomly assigning cluster centroids.
* Second, assign each point to the cluster with the nearest mean.
* Third, re-calculate the centroid of the cluster, by taking the mean (in all dimensions) of the points in that cluster.
* Repeat until the cluster centroids stop changing.

4. What is a time when you let others down in a professional setting, and what did you do to remedy it? Or, if you didn’t what could you have done?
* Personal growth story goes here.
* Do not highlight a grave personality flaw, confess to breaking an important social norm, or show really bad judgment.
* Best if the way you let people down was not really your fault, and you showed heroic ability in overcoming it and making it up to people.  Story about taking responsibility for your mistakes. 

5. What are you proudest of having accomplished and why?
* Use this to highlight traits that employers want to hear about.
* Do not explicitly mention the trait that you're highlighting.
* Stories with personal growth are best.

6. What are 3 predictions you have about the world 20 years from now?
* Do not make predictions about topics that are politically charged right now. 
* Try making predictions within an area that the interviewer cares about.
* Focus on optimistic predictions.
  
### Week 7:
1.  What is linear regression?
- Linear Regression is a statistical model that seeks to describe the relationship between some y variable and one or more x variables.

### Synonyms for "y variable"
- Dependent Variable
- Response Variable
- Outcome Variable 
- Predicted Variable
- Measured Variable
- Explained Variable
- Label

### Synonyms for "x variable(s)"
- Indepent Variable
- Explanatory Variable
- Regressor
- Covariate

### The Equation for a Line
2. What is the goal of linear regression?
- A common equation for a line is y = mx + b, where m is the slope of the line and b is the y-intercept. 
- Linear Regression seeks to **estimate** the slope and intercept values that describe a line that best fits the data points.

3. What is residual error?
- The residual error is the distance between points in our dataset and our regression line.

4. What is the most common way to minimize residual error?
- The most common method of estimating the slope and intercept is what's known as "Ordinary Least Squares" (OLS). (There are different methods of arriving at a line of best fit). OLS estimates the parameters that minimize the squared distance between each point in our dataset and our line of best fit. 

\begin{align}
SSE = \sum(y_i - \hat{y})^2
\end{align}

### week 11:
1. How are you today?
2. How is object-oriented programming different from functional programming? What are some advantages or disadvantages of each?
3. What is the relationship between modules, packages, dependencies, and namespaces in Python?
4.  What are some differences between Bayesian statistics and frequentist statistics? When might you use one over the other?
5.  How does a confusion matrix help you understand your model better?
6.  What is the alignment problem in artificial intelligence?
7.  We offer great flexibility in our employees’ scheduling? What would your ideal work week look like?

### Week 12:
1. So far in this sprint you've used SQLite, PostgreSQL, and MongoDB. For each of these, consider the following questions:

- What was easy about using this technology?
  * SQLite is easy to create, populate, and query databases locally either through a SQLite browser
  or in Python using the 'sqlite3' library.
  * PostgreSQL has the perks of SQLite but with the ability to handle much larger applications performing ACID compliant transactions.
    SQL query language shared among SQLite and PostgreSQL and other RDMS.
  * MongoDB's ease it's based on its flexibility as a "NOSQL" database program using JSON that allows for various features to inserted or ommited for each observation.
    Also MongoDB allows to work with huge databases that relational database management systems are not able to handle.
- What was hard about using this technology?
  * Learning how to properly use Python and its 'sqlite3' library to run SQL commands on a database.
  * Knowing how to give Postgre authentication to access databases.
  * Making a switch from SQL commands to commands in JSON-like format.
- What more would you like to learn about it?
  * Integrating these systems to a variety of Internet facing applications and using them to create robust data warehousing.

Write a summary in the style of a possible blog post, and bring the
questions/discussion to class. Bonus - later on, follow up and complete a real
blog post about different database technologies!

### week 13:

1. What about our company excites you the most? (_assume it is a company in a field you are *NOT* excited about_)
2. What is pipelining and how might you build one in Python?
3. What is the inverse of the squish function?
4. You are on a boat and throw a suitcase overboard. Does the water level increase?
5. What would you do if a teammate changed your work without consulting you first?
6. Whats your current biggest DS-related weakness and what are your plans on it?
7. You don’t have a Phd. or a degree in a requisite field.  Why should we hire you?

### Week 14:

1. What was your biggest achievement in your last job?
2. Do you prefer working in a team or alone? Why?
3. What are two or three specific applications of data science that get you most excited?
4. What are some key differences between Python and Scala?  
**A: Typing, run time, ease of learning, memory consumption, concurrency, and community support are, or can be, significantly different between these 2 languages.**  
5. What is a method for determining if statistics published in an article are either wrong or presented to support the author’s point of view?  
**A: Using the author(‘s)(s’) data, attempt to reproduce their analysis.**  
6. Explain what resampling methods are and why they are useful. What are their limitations?  
**A: Resampling methods enable estimation of sample descriptive statistics, model validation, and significance testing. Essentially, these methods help decrease uncertainties about how sample data may be used to make inferences about the population of interest. They also increase confidence in model selection. But these methods don't perfectly eliminate uncertainty.
Examples of resampling methods are cross validation, and bootstrap resampling.**  
7. In late 2016, a new recruit at Facebook designed a new feature to improve click-through rates on ads for political ads. They deployed their feature on a representative sample of users from across the country. The feature did not improve rates significantly in the general population, but it DID improve click-throughs for two groups: Female Texan college graduates between the ages of 30 and 35 and Male Floridian high-school graduates between 18 and 25.  The recruit’s manager was reviewing this data and had to decide whether to invest more time into testing/deploying it further.  What is the first question the manager should ask?  
**A: Is this feature/technique ethical?**  
8. What would make you quit a job you just started?

### Week 16:

1. Good morning! What do you think of our new offices here?
2. What is the difference between a deep and a shallow copy?
3. What the heck are *args and **kwargs and when are they used?
4. How do data scientists work with backend engineers?
5. Give an example of a time you would use a decision tree?
6. How many golf balls would fit into a Boeing 747?
7. What was the most difficult task you’ve faced in your last job and how did you overcome it?
8. If your manager asked you to do some task with data that you believed was unethical, how would you respond?

### Week 17:
1. What do you want to do by joining this position?
2. What are the ML concepts covered at Lambda School?
3. What is a lambda function in Python?
4. What is ROC AUC?
5. What are sampling techniques and which ones have you used?
6. Why is Python interpreted?
7. What are the disadvantages of an interpreted language?
