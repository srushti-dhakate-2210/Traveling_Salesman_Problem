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
    

In the dynamic algorithm for TSP, the number of possible subsets can be at most N \times 2^N. Each subset can be
solved in \mathcal{O}(N) times. Therefore, the time complexity of this algorithm would be
O(N^2* 2^N)




<H1>Conclusion</H1>
   




Depending on the size of the input cities, it is possible to find an optimal or a near-optimal solution using
various algorithms.
