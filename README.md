# comp309-aiml421-assignment-2-data-exploration-manipulation-and-modelling-solved
**TO GET THIS SOLUTION VISIT:** [COMP309/AIML421 — Assignment 2: Data Exploration, Manipulation and Modelling Solved](https://www.ankitcodinghub.com/product/comp309-aiml421-assignment-2-data-exploration-manipulation-and-modelling-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;95887&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP309\/AIML421 — Assignment 2: Data Exploration, Manipulation and Modelling Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (4 votes)    </div>
    </div>
<h1>1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Objectives</h1>
The goal of this assignment is to help you understand data manipulation and visualisation tools for machine learning. The purpose is to implement common data handling methods on real-world observations. To validate the effectiveness of the implemented methods, you are also required to perform data analysis tasks to draw useful conclusions. In particular, the following topics should be reviewed:

<ul>
<li>Cross Industry Standard Process for Data Mining (CRISP-DM)</li>
<li>Exploratory Data Analysis (EDA)</li>
<li>Data Preparation</li>
<li>Feature Manipulation</li>
</ul>
These topics are (to be) covered in weeks 4-6, but will also involve content from previous weeks. Research into online resources for AI and machine learning is encouraged. You are required to complete the following questions using data mining/machine learning tools introduced in the lectures – <em>Python </em>and/or <a href="https://orangedatamining.com/"><em>Orange</em></a><a href="https://orangedatamining.com/">.</a> For each part, make sure you finish reading all the questions before you start working on it, and your report for the whole assignment should <em>not exceed </em><em>8 pages </em>(note that this is a *maximum*, not a goal/target) with font size no smaller than 10.

<h1>2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Question Description</h1>
In this assignment, we are working on building machine learning models to predict house prices. The information contained in the given dataset is what a typical home buyer would want to know before making a purchase. More specifically, with <em>79 explanatory variables/features </em>describing different aspects of residential homes such as location, number of room, neighborhood, etc, you are required to predict the final price of homes.

What makes the house price in a city high or low? In this assignment, let’s try to answer this question by finding the most important features that affect a house price in the provided dataset. Your task in this assignment is to use data to discern the relationship between the house price (“SalePrice”) with the given features. <em>The dataset and the description of the variables/features are available at our </em><a href="https://ecs.wgtn.ac.nz/Courses/COMP309_2022T2/Assignments"><em>course website</em></a><a href="https://ecs.wgtn.ac.nz/Courses/COMP309_2022T2/Assignments">.</a>

<h2>2.1&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Part 1: Business and Data Understanding [40 marks]</h2>
The first part of this assignment is to explore the data. The task is to use CRISP-DM, EDA and data manipulation to define the machine learning tasks, understand, and prepare the data.

You should:

<ol>
<li>(20 marks) Perform an <strong>initial EDA </strong>on the given data to gain an understanding of the data. The analyses should explore the data from four different aspects including:
<ul>
<li>Describe the <em>summary statistics </em>about the data including number of instances, number of features, how many categorical and numerical features, respectively.</li>
<li>Find the <em>top 5 numerical features </em>highly correlated with the target variable (“SalePrice”) according to the <em>pearson correlation</em>, report the correlation values.</li>
<li>Plot the distributions of these 5 numerical features found in the previous question and the target variable using <em>histograms </em>with <em>10 bins</em>, one for each feature/variable, describe the shape of their distributions with <em>skewness </em>and <em>kurtosis </em>(use Scipy for obtaining <a href="https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.skew.html">skewness</a> and <a href="https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.kurtosis.html">kurtosis</a> values if you cannot do it in Orange), and tell <em>two patterns </em>from the histograms accordingly.</li>
<li>Check for missing values. Is there any missing values in the data? write a paragraph to briefly summarise the missing information regarding how many features contain missing values and at what percent.</li>
</ul>
</li>
</ol>
Provide answers to these four questions. Show how you get the answers in your code (if you use python)/workflow (if you use orange). Report your EDA methods and results in the report.

<ol start="2">
<li>(5 marks) Investigate the business understanding questions based on your exploration of the data. Two key business understanding questions (or business objectives) are “what factors affect the house price?” and “how do these factors affect the house price?”/“in which way do the factors affect the house price?”
<ul>
<li>Translate the two business questions into two data mining goals;</li>
<li>Select two machine learning paradigms, e.g. classification, regression, dimensionality reduction and so forth, that can help you achieve these goals. Provide justifications of your decision.</li>
</ul>
</li>
<li>(15 marks) EDA using clustering is very useful for understanding the important characteristics of the data. Provide a <strong>further EDA </strong>on the dataset using Hierarchical clustering on the 5 numerical features found in 1(b) to answer the question — “Does the house prices vary by neighborhood?”. Report the output dendrogram and any other plots and show how do they help you to answer the question.</li>
</ol>
<h2>2.2&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Part 2: Data Preparation and Machine Learning [60 marks]</h2>
Address the business question of “what factors affect the house price and in which way?” using the provided dataset. Note that for supervised learning, it is important to partition the data before data preparation to avoid data leakage. Before answering the following questions, you need to split the data into a training set and a test set with a 70-30 splitting (use a random state=309).

You should:

<ol>
<li>(20 marks) Determine and describe the data preprocessing steps applied to the provided dataset, e.g. handle missing data, encoding categorical data, normalise the data if necessary, and/or remove any unnecessary instances, these could be redundant instances, outliers or non-effective instances and so forth. Show the process in your code/workflow. Submit <em>a copy of the processed dataset </em>(in CSV format).</li>
<li>(15 marks) Utilise two different dimensionality reduction techniques to identify which features are irrelevant and/or redundant to predicting the house price. Report the dimension reduction process and remove redundant/irrelevant data. Show the process in your code/workflow.</li>
<li>(25 marks) Now approach data mining goals on your preprocessed data using machine learning methods.
<ul>
<li>With the <em>two groups </em>of features selected in previous question, use the <em>ordinary linear regression </em>and <em>ridge regression </em>(with <em>alpha=0.5</em>) for predicting the house prices. Comparing their results regarding the <em>mean squared errors </em>on the <em>training </em>set and the <em>test </em> Present and analyse the <em>learnt regression models</em>, and highlight your observations. Submit your code or workflow.</li>
<li>Using <em>Random Forest</em>, which is a more powerful ensemble regression method to predict the house price, compare with the results of linear regression and ridge regression, highlight your observations.</li>
</ul>
</li>
</ol>
<h2>2.3&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Part 3: Further Analyses (For AIML421 students only) [20 marks]</h2>
Use <em>two other regression techniques </em>to build prediction models for the house price with the same preprocessed data using in Part 2. Discuss the prediction results, compared with the regression techniques used in Part 2 and identify which technique is more suitable for this question and provide your justifications.

<strong>Relevant Data Files and Program Files</strong>

A soft copy of this assignment, the relevant data files are available from the <a href="http://ecs.victoria.ac.nz/Courses/COMP309_2022T2/Assignments">course homepage</a><a href="http://ecs.victoria.ac.nz/Courses/COMP309_2022T2/Assignments">.</a>

<h1>Assessment</h1>
<strong>Format: </strong>You can use any font to write the report, with a minimum of single spacing and 11 point size (hand writing is not permitted unless with approval from the lecturers). Reports are expected to be 2-8 pages for COMP309 students and 2-9 pages for AIML421 students. Reports exceeding the maximum page limit will be penalised.

<strong>Communication: </strong>A key skill required of a scientist is the ability to communicate effectively. No matter the scientific merit of a report, if it is illegible, grammatically incorrect, mispunctuated, ambiguous, or contains misspellings, it is less effective and marks will be deducted.

<strong>Late Penalties: </strong>The assignment must be submitted on time unless you have made a prior arrangement with the course coordinator or have a valid medical excuse (for minor illnesses it is sufficient to discuss this with the course co-ordinator). The penalty for assignments that are handed in late without prior arrangement is one grade reduction per day. Assignments that are more than one week late will not be marked.

<strong>Plagiarism: </strong>Plagiarism in programming (copying someone else’s code) is just as serious as written plagiarism, and is treated accordingly. Make sure you explicitly write down where you got code from (and how much of it) if you use any other resources asides from the course material. Using excessive amounts of others’ code may result in the loss of marks, but plagiarism could result in zero marks!

<h1>Submission</h1>
You are required to submit a single <em>.pdf </em>report PLUS the python code file (.ipynb or .py) or the orange workflow file (.ows) through the web submission system from the COMP309/AIML421 course website <em>by the due time</em>. Provide a <em>README.txt </em>file if you use any non-standard python libraries.
