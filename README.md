Download Link: https://assignmentchef.com/product/solved-cs-260-machine-learning-homework-4-spring-2020
<br>
The following questions are from <em>Understanding Machine Learning: From Theory to Algorithms </em>by Shai Shalev-Shwartz and Shai Ben-David. It can be found here http://www.cs.huji.ac.il/ shais/UnderstandingMachineLearning/ by courtesy of the authors.




<ol>

 <li> In this problem, you are asked to implement Adaboost algorithm using decision stump as the weak learner for binary classification. Consider the base hypothesis class of decision stumps over R<em><sup>d </sup></em>is <a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a></li>

</ol>

H<sub>DS </sub>= {<strong>x </strong>7→ sign(<em>θ </em>− <em>x<sub>i</sub></em>) : <em>θ </em>∈R<em>,i </em>∈ [<em>d</em>]}

and the sign function is defined as:

(

1 if <em>x </em>≥ 0

sign(<em>x</em>) =

−1 otherwise

Please report your answer of the following questions to Gradescope, and submit your source code to CCLE. Your answer will NOT be graded if we do not see your source code submission on CCLE. Note that, you are allowed to use other programming languages for your implementation. If so, you may need to create an csv data loader yourself and read the data from ./data/*.csv.

1

<ul>

 <li>Run the skeleton code, report the training and testing error obtained by the Adaboost model using decision stump implemented in scikit-learn.</li>

 <li>Implement ERM algorithm for Decision Stumps. Replace skeleton code line 52-55 with your implementation. Report the training error and testing error of a single decision stump with uniform distribution.</li>

 <li>Implement Adaboost algorithm based on the above implemented Decision Stump classifier. Replace line 118-120 with your own implementation. Plot the training error and testing error with respect to the number of iterations of training the Adaboost.</li>

 <li>Report the final training error and testing error of adaboost.</li>

</ul>

2

<a href="#_ftnref1" name="_ftn1">[1]</a> Note that the definition of decision stump is slightly different from the slides. Here we will follow the definition in the textbook.