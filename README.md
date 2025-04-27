# comp90049-project-1--naive-bayes-and-k-nearest-neighbour-for-predicting-stroke-solved
**TO GET THIS SOLUTION VISIT:** [COMP90049 Project 1- Naive Bayes and K-Nearest Neighbour for Predicting Stroke Solved](https://www.ankitcodinghub.com/product/comp90049-project-1-naive-bayes-and-k-nearest-neighbour-for-predicting-stroke-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;120103&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP90049  Project 1- Naive Bayes and K-Nearest Neighbour for Predicting Stroke Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
Submission: Source code (in Python) and (inline) responses

Overview

In this project, you will implement Naive Bayes and K-Nearest Neighbour (K-NN) classifiers. You will explore inner workings and evaluate behavior on a data set of stroke prediction, and on this basis respond to some conceptual questions.

Implementation

For marking purposes, a minimal submission should have a preprocess() function, which opens the data file, and converts it into a usable format. It should also define the following functions:

• split_data(), where you split your data sets into a training set and a hold-out test set.

• train(), where you build Naive Bayes and K-NN classifiers from the training data. You can create train your data as you answer the related question.

• predict(), where you use a trained model to predict a class for the test data. You can also do prediction as you answer the related question.

• evaluate(), where you will output the accuracy of your classifiers, or sufficient information so that it can be easily calculated by hand.

Packages

• pandas to read, split and preprocess the data

• sklearn to develop K-NN model and evaluate models

• numpy to implement scientific computing

• math to access to the mathematical functions

• matplotlib to create plots and visualizations

Data

For this project, we have adapted the Stroke data that have been used for stroke prediction [1], available online at (https://data.mendeley.com/datasets/x8ygrw87jw/1):

Some critical information:

1. File name: stroke_update.csv

2. 2740 instances

3. 10 attributes that include numeric and nominal attributes. The attributes avg_glucose_level, bmi and age are numeric. the rest of attributes are nominal.

4. The file stroke_features.txt explains each attribute

5. 2 classes, corresponding to the stroke outcomes: {0: No stroke, 1: Having stroke}

Questions

You should respond to questions 1-3. In question 2 (b) you can choose between two options for smoothing and two options for Naive Bayes formulation. A response to a question should take about 100–200 words, and make reference to the data wherever possible.

Question 1

Question 2

a Explain the independence assumption underlying Naive Bayes. What are the advantages and disadvantages of this assumption? Elaborate your answers using the features of the provided data. [no programming required] (1 mark)

b Implement the Naive Bayes classifier. You need to decide how you are going to apply Naive Bayes for nominal and numeric attributes. You can combine both Gaussian and Categorical Naive Bayes (option 1) or just using Categorical Naive Bayes (option 2). Explain your decision.

For Categorical Naive Bayes, you can choose either epsilon or Laplace smoothing for this calculation. Evaluate the classifier using accuracy and appropriate metric(s) on test data. Explain your observations on how the classifiers have performed based on the metric(s). Discuss the performance of the classifiers in comparison with the Zero-R baseline.

required] (1 mark)

Question 3 a Implement the K-NN classifier, and find the optimal value for K. (1 mark)

c Compare the classifiers (Naive Bayes and K-NN) based on metrics’ results. Provide a

comparatory discussion on the results. [no programming required] (1 mark)

Submission

Assessment

Changes/Updates to the Project Specifications

If we require any (hopefully small-scale) changes or clarifications to the project specifications, they will be posted on the LMS. Any addendums will supersede information included in this document.

Academic Misconduct

You are welcome — indeed encouraged — to collaborate with your peers in terms of the conceptualization and framing of the problem. For example, what the project is asking you to do, or what you would need to implement to be able to respond to a question.

Data references

10.1007/s10994-017-5629-5
