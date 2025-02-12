# Python-DSA-Graph1

https://leetcode.com/problems/find-center-of-star-graph/?envType=problem-list-v2&envId=graph
https://leetcode.com/problems/find-center-of-star-graph/solutions/5374686/easy-java-python3-c-solution-0-ms/?envType=problem-list-v2&envId=graph

Intuition:
The intuition behind this solution is that in a star graph, all the edges are connected to a single central node. Therefore, if we look at the first two edges, the central node will be present in both of them. We can use this property to find the center of the star graph.

Approach:
The approach used in the given code is to check if the first element of the first edge is present in the second edge. If it is, then the first element of the first edge is the center of the star graph. If not, then the second element of the first edge is the center of the star graph.
