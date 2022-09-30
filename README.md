# Traveling_Salesman_Problem
Name : Srushti Dhakate <br>
Sec : 5-A<br>
Roll : 25<br>



Given a set of nodes and distances as well as time taken to travel between every pair of nodes, the problem is to find
the shortest possible path that visits every node exactly once and returns to the starting point, such that:
<ul>
    <li>
        The path has the Least Distance Cost
    </li>
    <li>The path has the Least Time Cost</li>
    <li>
        The path has a Decent Distance and Time Cost
    </li>
</ul>

<h1>Collab Link </h1>
[Click Here 👉](https://colab.research.google.com/drive/1Q-WyCYDrN8HrRW0vft_kFBEFRAo92m_m?usp=sharing)



<H1>About Traveling Salesman Problem</H1>
    

In the TSP, given a set of cities and the distance between each pair of cities, a salesman needs to choose the
shortest path to visit every city exactly once and return to the city from where he started.
the nodes represent cities, and the values in each edge denote the distance between one city to another. Let's
assume a salesman starts the journey from the city A. According to TSP, the salesman needs to travel all the
cities exactly once and get back to the city A by choosing the shortest path. Here, the shortest path means the sum of the distance between each city travelled by the salesman, and it should be less than any other path.Here we use a
dynamic approach to calculate the cost function Cost(). Using recursive calls, we calculate
the cost function for each subset of the original problem.

<H1>Time Complexity Analysis
</H1>
    

In the dynamic algorithm for TSP, the time complexity of this algorithm would be
O(N^2* 2^N)


<H1>Test Cases</H1>


dist=([0,1,999,999],[999,0,1,999],[999,999,0,1],[1,999,999,0]) <br>
time=([0,999,999,2],[2,0,999,999],[999,2,0,999],[999,999,2,0])<br>
avg_dist_time=([0,3,999,999],[999,0,3,999],[999,999,0,3],[3,999,999,0])<br>

<H1>Screenshots of Sample Input</H1>

![Screenshot (834)](https://user-images.githubusercontent.com/86475735/193273549-282f1993-bb7e-405e-9f05-957e18524243.png)

![Screenshot (835)](https://user-images.githubusercontent.com/86475735/193273602-2318071a-a00f-4634-b553-eb7ba471e672.png)
![Screenshot (836)](https://user-images.githubusercontent.com/86475735/193273791-c57eb646-5638-45c1-a016-54952af8f307.png)
![Screenshot (837)](https://user-images.githubusercontent.com/86475735/193273905-24486d24-e08b-4b46-abc0-cf99845caa5d.png)

![Screenshot (838)](https://user-images.githubusercontent.com/86475735/193274013-ce550bca-c2fa-42ce-a5c3-9487ca4e47b6.png)


![Screenshot (839)](https://user-images.githubusercontent.com/86475735/193274071-16593632-7c48-4c66-a7ea-ae73ccedf5a4.png)
<H1>Conclusion</H1>
   




Depending on the size of the input cities, it is possible to find an optimal or a near-optimal solution using
various algorithms.
