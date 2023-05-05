Download Link: https://assignmentchef.com/product/solved-data-structures-and-algorithms-cs-f211-lab-sheet-8
<br>
<ol>

 <li>You joined an analytics company as an intern. Since you were new you were given an easy task to start with. Every day you will be given a number and you have to calculate the medians of all the numbers you have received till date. You want to automate the process and you have to complete the task in less than O(<strong><em>n<sup>2</sup>) </em></strong>time.</li>

</ol>




<strong>Input: <em>n</em></strong> (total number of days) <strong><em>n</em></strong> integers (separated by space)

<strong> </strong>

<strong>Output: </strong>

<strong><em>n</em></strong> integers each on a single line denoting the median of all the numbers given to you till the <strong><em>i</em></strong><sup>th</sup> date. Print them in float format.




<strong>Example: </strong>

6

12 4 5 3 8 7 <strong>Answer: </strong>

12.0

8.0

5.0

4.5

5.0

6.0




<ol start="2">

 <li>Assume that you are managing a pizza store and you have to schedule different pizza requests. Let us consider that <strong><em>i</em></strong><sup>th </sup>request comes at time <strong><em>t<sub>i</sub></em></strong> and take <strong><em>s<sub>i</sub></em></strong> seconds to be processed.</li>

</ol>

For example, let us consider that there are three requests that arrive at <strong><em>t<sub>1</sub></em></strong> = 0, <strong><em>t<sub>2</sub></em></strong> = 1, <strong><em>t<sub>3</sub></em></strong> = 2 with processing time <strong><em>s<sub>1</sub></em></strong> = 3, <sub> </sub><strong><em>s<sub>2</sub></em></strong> = 9, <sub> </sub><strong><em>s<sub>3</sub></em></strong> = 6. Now, if you apply first come-first serve rule, then request 1 executes first finishing at <strong><em>t</em></strong> = 3, then request 2 which finishes at <strong><em>t</em></strong> = (3 + 9) = 12 and then request 3 which finishes at  <strong><em>t</em></strong> = (12 + 6) = 18. Remember that when one process is running it cannot be interrupted by any others. Now we define waiting time for each process as:

<strong>Waiting Time = (Time at which the task is done) – (Time at which the task arrived).</strong>

So, waiting time of three processes are 3, 11, &amp; 16 respectively. The average waiting time in this case is (3 + 11 + 16) / 3 = 10. This is not an optimal solution. After serving the first customer at time <strong><em>t</em></strong> = 3, you can choose to serve the third customer. In that case, the waiting time will be 3, 7, &amp; 17 respectively. Hence the average waiting time is (3 + 7 + 17) / 3 = 9. Given <strong><em>t<sub>i</sub></em></strong>’s and <strong><em>s<sub>i</sub></em></strong>’s, your goal is to find the minimum average waiting time.




<strong>Input: </strong>

In the first line, you will be given an integer <strong><em>n</em></strong> (number of requests).

In the next <strong><em>n </em></strong>lines, two space-separated integers will be given. The first is arrival time and second is processing time of each request.




<strong>Output: </strong>

Minimum average waiting time.




<ol start="3">

 <li>Write a program to check for balanced parentheses in an expression. For example, your code should return true for “[()]{}{[()()]()}” while false for “{(]}”. The expression may contain other characters as well (other than parentheses).</li>

</ol>

<strong> </strong>

<strong> </strong>

<strong>Input: </strong>

A string containing the expression.

<strong> </strong>

<strong>Output: </strong>

True if its balanced, else false.




<ol start="4">

 <li>You love cookies. You have <strong><em>n</em></strong> cookies with you. Let us assume that the <strong><em>i</em></strong><sup>th </sup>cookie has <strong><em>A[i]</em></strong> sweetness value. You want the sweetness values of all your cookies to be greater than or equal to value <strong><em>K</em></strong>. To do this, you repeatedly mix two cookies with the least sweetness values. You create a special combined cookie with:</li>

</ol>

<strong>Sweetness value = (Least sweetness value + 2*second least sweetness value). </strong>

You repeat this procedure until all the cookies in your collection have a sweetness greater than or equal to <strong><em>K</em></strong>. Calculate the number of operations required.




<strong>Input:  </strong>

The first line consists of integers <strong><em>n</em></strong> – the number of cookies and <strong><em>K</em></strong> – the minimum required sweetness, separated by a space.

Each of the next lines contains <strong><em>n</em></strong> integers describing the array <strong><em>A</em></strong> where <strong><em>A[i]</em></strong> is the sweetness of the cookie.




<strong>Output: </strong>

Print exactly one integer — the number of operations needed.




<strong>Example: </strong>

<strong>Input: </strong>

6 7

1 2 3 9 10 12




<strong>Output: </strong>

2




<ol start="5">

 <li>Given an array of digits (values are from 0 to 9), find the minimum possible sum of two positive numbers formed from digits of the array. All digits of given array must be used to form the two numbers.</li>

</ol>




<strong>Input: </strong>

A single containing the digits separated by space.




<strong>Output: </strong>

The sum.




<strong>Example: </strong>

<strong>Input:</strong>

6 8 4 5 2 3

<strong> </strong>

<strong>Output:</strong>

604




<strong>Explanation: </strong>

The minimum sum is formed by numbers 358 and 246.




<ol start="6">

 <li>Design a stack that supports push, pop, and retrieving the minimum element in constant time. Make it a menu-driven program where the 3 operations can be done any number of times. The user will be prompted to enter the type of operation and the associated data value.</li>

</ol>




<ol start="7">

 <li>Naruto was once interested in sum of entire array. However, now he is obsessed with minimum element in the array. But in order to make things more interesting he decided to find the minimum element of every sub array and then sum it. Help Naruto find the sum.</li>

</ol>

<strong>Input: </strong>

The first line contains the size <strong><em>N</em></strong> of the array.

The second line contains the <strong><em>N </em></strong>integers separated by space.




<strong>Output: </strong>

The sum.




<strong>Example: </strong>

<strong>Input:  </strong>

4

3 1 2 4




<strong>Output: </strong>

17




<strong>Explanation: </strong>

The subarrays are {3}, {1}, {2}, {4}, {3, 1}, {1, 2}, {2, 4}, {3, 1, 2}, {1, 2, 4} and {3, 1, 2, 4}. The sum = 3 + 1 + 2 + 4 + 1 + 1 + 2 + 1 + 1 + 1 = 17.




<strong>Input: </strong>

4

1 2 3 4




<strong>Output </strong>

20




<ol start="8">

 <li>The city of Matrix is tricky. You are given a <strong><em>n*n</em></strong> binary matrix map of the city. You will get life points if the submatrix you decide to work on has a single 1. Given the map find the number of submatrices that will give you life points. The submatrices are not essentially square matrices.</li>

</ol>




<strong>Input: </strong>

The first line contains the value of <strong><em>n</em></strong>.

Next, the matrix is entered row-by-row, each row input in a new line.




<strong>Output: </strong>

The number of submatrices.




<strong>Example: </strong>

<strong>Input </strong>

3

0 0 0

0 0 0

0 0 0




<strong>Output </strong>

0




<strong>Input </strong>

3

0 0 0

0 1 0

0 0 0




<strong>Output </strong>

16

<strong>Explanation: </strong>

The submatrices are:

<table width="701">

 <tbody>

  <tr>

   <td width="180">1,  0   1,  1    0,  <sup>0</sup>,   <sup>1</sup>,  01 0</td>

   <td width="25">1</td>

   <td width="81">00,   1 ,   <sup>0</sup>00</td>

   <td width="51"><sup>0</sup>,   <sup>0 </sup>1 1</td>

   <td width="51"><sup>0</sup>,   <sup>0 </sup>0 0</td>

   <td width="51"><sup>1</sup>,   <sup>1 </sup>0 0</td>

   <td width="51"><sup>0</sup>,   <sup>0 </sup>0 0</td>

   <td width="25">01</td>

   <td width="46">0,  00 0</td>

   <td width="25">10</td>

   <td width="51">0<sup>0</sup>,   000</td>

   <td width="51">0 01,   10 0</td>

   <td width="17">00,0</td>

  </tr>

 </tbody>

</table>

0 0 0

0 1 0

0 0 0







<ol start="9">

 <li>Hawk Eye is a sharp shooter. He has been training for years before joining as Shield Agent. He has an ability that helps him to aim long distance targets with pinpoint accuracy. Assuming he is currently standing on Stark tower and trying to aim at Thanos whose is standing on the last building in that row. He can only shoot him if the building heights are arranged in a non-increasing order. Thor can help Hawk Eye by performing 2 operations, either cut the building by one floor or add some junk on the building to increase its height by one floor. Find the minimum operations needed by Thor.</li>

</ol>




<strong>Input: </strong>

The first line contains the number of towers.

The second line contains the heights of the towers separated by spaces.




<strong>Output: </strong>

The number of operations required.




<strong>Example: </strong>

<strong>Input: </strong>

4

3 1 2 1




<strong>Output: </strong>

1




<strong>Input: </strong>

4

3 1 5 1




<strong>Output: </strong>

4




<strong>Input: </strong>

4

1 5 5 5




<strong>Output: </strong>

4




<ol start="10">

 <li>Zolo is stuck in a traffic due to dysfunctional traffic light. Zolo is a professional hacker and he can get into the system and change the state of the light. His planet has different types of traffic lights such that there are <strong>N bulbs </strong>on the traffic board and only when all of them are green(<strong>G</strong>) the cars can pass. There are <strong>2 </strong>other states also which the bulb can show – Red(<strong>R) &amp; </strong>Yellow(<strong>Y</strong>). Note that the lights are designed such that they follow a state change cyclic pattern as follows:</li>

</ol>

<strong>R——&gt;Y——&gt;G——-&gt;R</strong>

Once Zolo gets into the system he can select any position <strong><em>i</em></strong> and update all elements between <strong><em>i</em> to min(N, <em>i</em> + K – 1) </strong> by increasing their state by 1.This whole process takes <strong>1 sec</strong> and he can repeat this process any number of times until he gets all lights = <strong>G .</strong> Find the minimum time to do the process as Zolo is getting late for work.

<strong>Input: </strong>

The first line contains <strong>N K</strong>

The second line describes the current status of each bulb as an array whose each element can either be <strong>G or Y or R</strong>




<strong>Output:</strong>

The minimum amount of time required to clear the traffic jam.

<strong>Constraints:</strong>

1<strong>&lt;=N, K&lt;=</strong>100000

<strong> </strong>

<strong>Example: </strong>

<strong>Input: </strong>

4 2

R Y G Y




<strong>Output: </strong>

5













****************************





