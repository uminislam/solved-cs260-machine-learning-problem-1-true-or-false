Download Link: https://assignmentchef.com/product/solved-cs260-machine-learning-problem-1-true-or-false
<br>
<table width="620">

 <tbody>

  <tr>

   <td width="524"></td>

   <td width="96">.</td>

  </tr>

 </tbody>

</table>

<h1>Problem 1. True or False</h1>

Decide whether the following statements are true or false. Justify your answers.

<ul>

 <li>If classifier <em>A </em>has smaller training error than classifier <em>B</em>, then classifier <em>A </em>will have smaller generalization (test) error than classifier <em>B</em>.</li>

 <li> The VC dimension is always equal to the number of parameters in the model.</li>

 <li> For non-convex problems, gradient descent is guaranteed to converge to the global minimum.</li>

</ul>

<h1>Problem 2. Multiple choice questions</h1>

Choose the correct answer and justify your answer.

(a) (20 pt) Which of the following is not a possible growth function√                <em>m</em><sub>H</sub>(<em>N</em>) for some hypothesis set? (1) 2<em><sup>N</sup></em>

(2) 2 <em><sup>N </sup></em>(3) 1 (4) <em>N</em><sup>2 </sup>− <em>N </em>+ 2 (5) none of the other choices

<h1>Problem 3. Proximal Gradient Descent</h1>

Consider solving the following problem

<em>,</em>

<em>w</em>

where <em>X </em>∈ <em>R<sup>n</sup></em><sup>×<em>d </em></sup>is the feature matrix (each row is a feature vector), <em>y </em>∈ <em>R<sup>n </sup></em>is the label vector, k<em>w</em>k<sub>1 </sub>:= <sup>P</sup><em><sub>i </sub></em>|<em>w<sub>i</sub></em>| and <em>λ &gt; </em>0 is a constant to balance loss and regularization. This is known as the Lasso regression problem and our goal is to derive the “proximal gradient method” for solving this.

<ul>

 <li>(10 pt) The gradient descent algorithm cannot be directly applied since the objective function is nondifferentiable. Discuss why the objective function is non-differentiable.</li>

 <li>(30 pt) In the class we showed that gradient descent is based on the idea of function approximation. To form an approximation for non-differentiable function, we split the differentiable part and non-differentiable part. Let, as discussed in the gradient descent lecture we approximate <em>g</em>(<em>w</em>) by</li>

</ul>

<em>.</em>

In each iteration of proximal gradient descent, we obtain the next iterate (<em>w<sub>t</sub></em><sub>+1</sub>) by minimizing the following approximation function:

<em>w<sub>t</sub></em><sub>+1 </sub>= argmin<em>g</em>ˆ(<em>w</em>) + <em>λ</em>k<em>w</em>k<sub>1</sub><em>. </em><em>w</em>

Derive the close form solution of <em>w<sub>t</sub></em><sub>+1 </sub>given <em>w<sub>t</sub>,</em>∇<em>g</em>(<em>w<sub>t</sub></em>)<em>,η,λ</em>. What’s the time complexity for one proximal gradient descent iteration?

1