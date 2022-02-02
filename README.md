# aasignment2-gopireddy
# REETHU #
### Masqati ###
Kentucky Fried Chicken, which began as roadside restauarnt serving chicken with huge variance, has now spread all over the world as the most well-known & preferred joint for chicken included food itemsand meals. You get a whole lot of options including ** burgers, fried chicken, rice bowls & overall meals ** etc.
--------------------------

# Way to my favourite restaurant

1. Catch a flight to India
2. Go to Hyderabad
3. enroute to Lb nagar
4. There we will find a place call kfc

[About me](AboutMe.md)

---------------------------
# MY FAV SPORTS

I like playing sports.
Playing badminton,cricket,table tennis and basketball,
playing these releases the tension

-----------------------------
|Name        |Location|Cost|
|------------|--------|----|
|badminton   |park    |$50 |
|cricket     | park   |$30 |
|table tennis| park   |$40 |
|basketball  |park    |$60 | 
-----------------------------

-------------------------------------------
# Quotes

>Everything is hard before it is easy. *—Johann Wolfgang von Goethe*

>Anyone who has never made a mistake has never tried anything new. *—Albert Einstein*

---------------------------------------------
# Graphs

A Graph is a non-linear data structure consisting of nodes and edges. The nodes are sometimes also referred to as vertices and the edges are lines or arcs that connect any two nodes in the graph.Graphs are used to solve many real-life problems. Graphs are used to represent networks. The networks may include paths in a city or telephone network or circuit network. Graphs are also used in social networks like linkedIn, Facebook. For example, in Facebook, each person is represented with a vertex( or node).Each node is a structure and contains information.
<https://www.geeksforgeeks.org/graph-data-structure-and-algorithms/>
 ```
 vector<vector<int>> adj;  // adjacency list representation
 int n; // number of nodes
 int s; // source vertex

 queue<int> q;
 vector<bool> used(n);
 vector<int> d(n), p(n);

 q.push(s);
 used[s] = true;
 p[s] = -1;
 while (!q.empty()) {
   int v = q.front();
  q.pop();
   for (int u : adj[v]) {
       if (!used[u]) {
           used[u] = true;
           q.push(u);
           d[u] = d[v] + 1;
           p[u] = v;
       }
   }
 }
 ```

<https://cp-algorithms.com/graph/breadth-first-search.html>


