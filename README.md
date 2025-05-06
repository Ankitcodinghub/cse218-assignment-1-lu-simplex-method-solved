# cse218-assignment-1-lu-simplex-method-solved
**TO GET THIS SOLUTION VISIT:** [CSE218 Assignment 1-LU & Simplex Method Solved](https://www.ankitcodinghub.com/product/cse218-assignment-1-lu-simplex-method-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96861&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE218 Assignment 1-LU \u0026amp; Simplex Method Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Assignment #1

Please read the instructions carefully. Note that, your assignment will be evaluated using an auto-grader. Therefore, 100% compliance with the specifications is a must. Otherwise, you may end up with poor marks.

In this assignment, you are required to find solutions of a set of simultaneous linear equations using LU decomposition. A set of n linear equations consisting of n unknowns 𝑥1, 𝑥2, 𝑥3, …, 𝑥𝑛 can be written in the following form:

𝑎11𝑥1 +𝑎12𝑥2 +……+𝑎1𝑛𝑥𝑛 =𝑏1 𝑎21𝑥1 + 𝑎22𝑥2 + ……..+ 𝑎2𝑛𝑥𝑛 = 𝑏2 ……………………………………… ……………………………………… 𝑎𝑛1𝑥1 + 𝑎𝑛2𝑥2 + ……..+𝑎𝑛𝑛𝑥𝑛 = 𝑏𝑛

In matrix form, this set of equations can be expressed as:

AX = B ……………………………………………………… (1)

Where,

𝑎11 𝑎12 … 𝑎1𝑛

A = [𝑎21 𝑎22 … 𝑎2𝑛] …………

𝑎𝑛1 𝑎𝑛2 … 𝑎𝑛𝑛 𝑥1

X = [𝑥2] …

𝑥𝑛 𝑏1

B = [𝑏2] …

𝑏𝑛

In LU decomposition, you are required to decompose the matrix A such that, A = LU ……………………………………………………… (2)

where L is a lower triangular matrix and U is an upper triangular matrix. Then, from (1) we get,

LUX = B ……………………………………………………… (3)

Let, UX = Y ………………………………………………….. (4)

Then from (3),

LY = B, where Y is an n × 1 matrix of artificial variables and

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
𝑦1

Y = [𝑦2] …

𝑦𝑛

We can solve for Y easily since L is a lower triangular matrix. Substituting the value of Y in (4), we can find the solutions for X.

You are required to write a python script named 1.py which will take the matrices A and B as inputs and perform the following tasks:

Task 1: Calculate and print the L matrix. (6 marks)

Task 2: Calculate and print the U matrix. (6 marks)

Task 3: Determine whether the set of linear equations has a unique solution or not. A unique solution is unachievable if an entire row in the U matrix becomes zero. Print “No unique solution” (without the quotes) if no unique solution can be found and terminate the program. Otherwise, continue to the following tasks. (2 marks)

Task 4: Calculate and print the Y matrix. (3 marks) Task 5: Calculate and print the X matrix (3 marks)

The input will be from a file named in1.txt which must reside in the same directory as that of the python source file 1.py

The format of the input file in1.txt will be as followed:

Line 1 will contain an integer n, denoting the number of variables and equations in the set of equations where 2 ≤ n ≤ 100. After that, there will be n lines each containing n double values separated by a space. These n lines constitute the A matrix. Then, there will be n lines each containing a double value. These n lines constitute the B matrix.

All outputs (print statements for this assignment) must be in a file named out1.txt. Outputs printed in the console will not be considered for evaluation. The format of the output file will be as followed:

First n lines should contain n double values each separated by a space. These n lines should constitute the L matrix.

A blank line should be printed after that.

Next n lines should contain n double values each separated by a space. These n lines should constitute the U matrix.

A blank line should be printed after that.

If there is no unique solution for the set of equation, print “No unique solution” (without the quotes) and terminate the program. Otherwise, there should be n more lines containing a double value in each line. These n lines constitute the Y matrix.

A blank line should be printed after that.

Next n lines should contain a double value in each. These n lines should constitute the X matrix.

A sample input file and output file are attached for your convenience.

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Assignment #2 (20 Marks)

In this assignment, you have to develop a program implementing the popular simplex method for LP maximization problem only. Please follow the specifications carefully:

INPUT

(i) You need to implement simplex method for maximization problem only. So, you have to consider only the “less than or equal to” inequality relations.

(ii) You must take input from a file named “in2.txt”. The input file must reside in the same directory as that of your python script. The structure of the input file is described below- &lt;Coefficients of Objective function&gt;

&lt;Constraints&gt; &lt;Constraints&gt; … &lt;Constraints&gt;

<ul>
<li> &nbsp;The first line will contain the coefficients of the variables in the objective function. If we have n variables, then this line should have n values (can be float) in a space separated manner.</li>
<li> &nbsp;Then there will be m lines for the m “less than or equal to” constraints. Please note that, no input is necessary for constraints like X1 ≥ 0. For this assignment, you can assume that, these constraints are present by default.</li>
<li> &nbsp;Each of these m lines will have n + 1 values (n values for the coefficients of each variable and 1 value for the right hand side) in a space separated manner. For example, for a constraint X1 + 3X2 ≤ 15, the input line should be “1 3 15” (For two variables). For a constraint X2 ≤ 10, the input line should be “0 1 10” (For two variables).
Consider the following maximization problem: Maximize Z = 12X1 + 10X2 subject to

5X1 + 4X2 ≤ 1700

X1 +X2 ≤7

4.5X1 + 3.5X2 ≤ 1600

X1 +2X2 ≤500

X1,X2 ≥0

For this problem, the input file should look like the following: 12 10

5 4 1700

1 17

4.5 3.5 1600 1 2 500
</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
OUTPUT

(i) You must output the tableu of each step. The precision of the double values should be upto 2 decimal places after the decimal point. You can output in the console or in a file, which ever one you prefer. (16 marks)

(ii) You must output the maximum value of the objective function along with the corresponding value of the variables. (4 marks)

BONUS

Show a graph highlighting the feasible region (For two variables problem only). (5 marks)

Special notes

1. Your code must be in Python 3.

2. You cannot use any library other than numpy and matplotlib.

3. For assignment 1, you are not allowed to change the order of the rows of matrices A and B while performing the calculations.

4. For assignment 1, while printing, the precision of the double values should be up to 4 decimal places after the decimal point. For assignment 2, the precision of the double values should be upto 2 decimal places after the decimal point. Note that, this precision truncation should be performed in the printing step only, not in the intermediate calculation steps.

5. The input and output filenames must match exactly with the specification and the files must reside in the same directory as the python source file.

6. Any sort of plagiarism (from friends, Internet or any other source) will be dealt with a 100% penalty of the assignment marks.

&nbsp;

</div>
</div>
</div>
