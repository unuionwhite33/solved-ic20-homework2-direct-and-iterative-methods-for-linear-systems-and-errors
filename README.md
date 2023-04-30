Download Link: https://assignmentchef.com/product/solved-ic20-homework2-direct-and-iterative-methods-for-linear-systems-and-errors
<br>



<h1>Exercise 1</h1>

<ul>

 <li>Write a function that implements the Gaussian elimination method.</li>

 <li>Write a script that calls the function on a sparse matrix (represented in the standard way, without using a compact representation), having a given sparsity value.</li>

 <li>Use the command <strong><sub>spy</sub></strong> to visualize the sparsity pattern at each iteration of the Gaussian elimination algorithm and produce a movie to show how the final upper triangular matrix fills up.</li>

 <li>Compute the sparsity at each iteration and show it on a graph.</li>

</ul>




<h1>Exercise 2</h1>

<ul>

 <li>Write a function for two out of three pivoting technique for the Gaussian elimination method, that is function GEPP for Partial Pivoting, GECP for Complete pivoting, GERP for Rook Pivoting.</li>

 <li>Write a script that calls each function on random generated matrices of size n&gt;= 50, and compute the execution time (using the same matrix for the two chosen techniques), averaging on a set of matrices large enough.</li>

 <li>For each matrix compute the condition number for linear systems</li>

 <li>Show on a graph the execution time for the Gaussian elimination without pivoting and for the two pivoting techniques.</li>

</ul>




<h1> Exercise 3</h1>

<ul>

 <li>Write a function that implements the Jacobi iterative method for a sparse matrix represented using a compact format at your choice.</li>

 <li>Write a function that implements the Gauss-Seidel iterative method for a sparse matrix represented using a compact format at your choice.</li>

 <li>Write a script that calls each function on random generated matrices of size n&gt;= 50, using the two following criteria for checking the convergence of the two methods:</li>

 <li>E1: Error obtained by using the exact values (found with Exercise 1 or Matlab function): E1 <em>e</em>(<em>k</em>)  <em>x</em><em>x</em>(<em>k</em>) &lt; ε</li>

 <li>E2: Difference between two successive iterations: E2 <em>e</em><sup>(<em>k</em>) </sup> <em>x</em><sup>(<em>k</em>) </sup><em>x</em><sup>(<em>k</em></sup><sup></sup><sup>1) </sup>&lt; ε</li>

</ul>

Show E1 and E2 on a graph (to compare the number of iterations needed to stop), averaging on a set of matrices.




<h1>Exercise 4</h1>

<ul>

 <li>Implement the Jacobi iterative method for a sparse matrix, represented using a compact format at your choice, using the Parallel toolbox of Matlab.</li>

 <li>Show on a graph the serial time, the parallel time and the overhead introduced by parallelization (see slides Matlab Part 2, pages 31-55) averaging on a set of matrices.</li>

</ul>







<h1>Sparse matrices collection</h1>

Sparse matrices can be found in the <em>SuiteSparse Matrix Collection</em> at the link: <a href="https://sparse.tamu.edu/">https://sparse.tamu.edu/</a>




<em>The SuiteSparse Matrix Collection (formerly known as the University of Florida Sparse Matrix Collection), is a large and actively growing set of sparse matrices that arise in real applications. The Collection is widely used by the numerical linear algebra community for the development and performance evaluation of sparse matrix algorithms. </em>

<em><u>Note that you can search square matrices or example filtering by keyword “linear systems” and set</u> <u>the constant vector b as a vector of ones (or zeros).</u>  </em>


