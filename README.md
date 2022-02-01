# assignment2-Boppidi


# Ram Reddy. Boppidi

###### KFC
we do have walmart, dominos , **dollar tree** and Hyvee as sorroundings to the KFC and there is **kawasaki showroom** as well.

---

# Directions to food location from the airport
###### Nearest Airport to food location- Kansas
1. Take a safe ride from kansas to Maryville.
2. will take 70 miles to reach Maryville.
3. Before entering to maryville, there will be a landmark- kawasaki motors.
4. From  kawasaki motors to KFC, it is a distance of 1.4mi.
5. will see KFC on the left hand side, with walmart straight infront of it.

#### Below are the items, I recommend to taste at least once 

* Non-vegetarian
   * 3 Pc. Chicken Box
   * Crispy colonel Box
   * 8 Piece Chicken
   * 3 Pc. Tenders combo

* Drinks & fries
   * Coco cola
   * waffle potato fries
   * Dew
   * pepsi

[Link to AboutMe](AboutMe.md)

---

# Table

The following table describes Sports activities that someone should try.

|     Name of the Sport   |       Location    |      Cost    |    
|           ---                   |           ---                 |       ---          |
|    Hockey  |     India    |       60$          |
|     Cricket                   |       England               |       70$         |
|     Football                 |   France   |      70$         |
|     Badminton                      |     Australia              |       50$          |

---

# Pithy Quotes
>  "Either write something worth reading or do something worth writing." —*Benjamin Franklin*   <br>
    
>  "Anyone who has never made a mistake has never tried anything new." —*Albert Einstein*

---

# Code Fencing
> Breadth First Traversal (or Search) for a graph is similar to Breadth First Traversal of a tree (See method 2 of this post). The only catch here is, unlike trees, graphs may contain cycles, so we may come to the same node again. To avoid processing a node more than once, we use a boolean visited array. For simplicity, it is assumed that all vertices are reachable from the starting vertex.

Link to source <https://www.geeksforgeeks.org/breadth-first-search-or-bfs-for-a-graph>
```
<pre>
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
</pre>
```

Link to source code <https://cp-algorithms.com/graph/breadth-first-search.html>

> Depth First Traversal (or Search) for a graph is similar to Depth First Traversal of a tree. The only catch here is, unlike trees, graphs may contain cycles (a node may be visited twice). To avoid processing a node more than once, use a boolean visited array.

Link to source <https://www.geeksforgeeks.org/depth-first-search-or-dfs-for-a-graph/?ref=gcse>
```
<pre>
 vector<vector<int>> adj; // graph represented as an adjacency list
   int n; // number of vertices

   vector<bool> visited;

   void dfs(int v) {
    visited[v] = true;
    for (int u : adj[v]) {
        if (!visited[u])
            dfs(u);
    }
}
</pre>
```

Link to source code <https://cp-algorithms.com/graph/depth-first-search.html"> Link to source code>








