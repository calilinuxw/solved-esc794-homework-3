Download Link: https://assignmentchef.com/product/solved-esc794-homework-3
<br>
<strong>1 </strong>Solve the following quadratic program using the basic active set method discussed in class.

Minimize

with <em>P </em>=diag(2     = [1 1 1] subject to

<table width="131">

 <tbody>

  <tr>

   <td width="97"><em>x</em>1 + <em>x</em>2 + <em>x</em>3</td>

   <td width="26">≥</td>

   <td width="8">4</td>

  </tr>

  <tr>

   <td width="97"><em>x</em><sub>3</sub></td>

   <td width="26">≤</td>

   <td width="8">2</td>

  </tr>

  <tr>

   <td width="97"><em>x</em><sub>2</sub></td>

   <td width="26">≤</td>

   <td width="8">0</td>

  </tr>

  <tr>

   <td width="97"><em>x</em><sub>1</sub></td>

   <td width="26">≤</td>

   <td width="8">4</td>

  </tr>

 </tbody>

</table>

<ul>

 <li>Start from a feasible point of your choice and a suitable initial guess for the active set.</li>

 <li>Show every step of the iterations until the solution is found. You can do this as comments in the Matlab code.</li>

 <li>How do you know that the exact solution has been found?</li>

 <li>Solve the same problem using quadprog and verify that your answer matches this solution.</li>

</ul>

<strong>2</strong>

Install the qpOASES solver (Matlab interface) in your computer. Obtain it from https://projects.coin-or.org/qpOASES/wiki/QpoasesDownload

Instructions for installation on Linux and Windows, as well as solver usage and examples is found in the documentation:




<ul>

 <li>Focus on section 6.1 of the documentation. You will need a C++ compiler enabled in Matlab. Linux users: you can use gcc. Windows users: use the free MinGW compiler available from the add-ons tab from within Matlab. You may need a Mathworks account.</li>

 <li>Linux users: I found a compilation error which was easily fixed by changing a line in m. See: https://projects.coin-or.org/qpOASES/ticket/84</li>

 <li>Make sure you can run the examples supplied with the code.</li>

 <li>Solve the QP problem of question 1 above using qpOASES, without additional bounds on <em>x </em>or upper bounds on <em>Ax</em>.</li>

 <li>Use tic and toc to time execution of each solver. Times will vary depending on processor loads, so do this test many times and report on the min, max and mean times of each solver. Histograms would be nice.</li>

</ul>

<strong>3</strong>

Solve Prob. 3 in Chapter 2 of the textbook by Gru¨ne and Pannek. You must indicate the specific comparison functions that were used in your proof.