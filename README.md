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
    

In the dynamic algorithm for TSP, the number of possible subsets can be at most N \times 2^N. The time complexity of this algorithm would be
O(N^2* 2^N)


<H1>Test Cases</H1>

dist=([0,120,634,164],[148,0,32,12],[100,670,0,92],[140,254,694,0]) <br>
time=([4,2,4,1],[6,2,8,2],[10,6,3,5],[12,15,6,7])<br>
avg_dist_time=([0,126,134,257],[615,0,132,143],[130,116,0,679],[112,125,160,0])<br>

<H1>Screenshots of Sample Input</H1>

![Screenshot (828)](https://user-images.githubusercontent.com/86475735/193115200-e62c2824-b81c-472b-b7f7-f66ff27c96d0.png)

![Screenshot (829)](https://user-images.githubusercontent.com/86475735/193115224-b1f8fad4-7efb-4ebf-9776-c401bc0ac441.png)

![Screenshot (830)](https://user-images.githubusercontent.com/86475735/193115270-9cb4c757-6b7b-4826-b0f2-075b76b07b38.png)
![Screenshot (831)](https://user-images.githubusercontent.com/86475735/193115290-441734a8-9d1a-491c-b138-bf19a8ed98b3.png)
![Screenshot (832)](https://user-images.githubusercontent.com/86475735/193115315-325a4588-7ef1-4e15-a594-b81a10c31147.png)
![Screenshot (833)](https://user-images.githubusercontent.com/86475735/193115347-4bf41abc-4c37-4d8c-b177-22a0465ed3e9.png)

<H1>Conclusion</H1>
   




Depending on the size of the input cities, it is possible to find an optimal or a near-optimal solution using
various algorithms.
