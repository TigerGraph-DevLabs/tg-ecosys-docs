

## As a Data Scientist 

Looking to get your hands on a real notebook and start to impelement TigerGraph with your Data Science stack? Checkout this notebook to get started!

<script src="https://gist.github.com/HerkTG/2f2ed0f40962ca5ffa9aac9ab3880b0f.js"></script>

## As a Graph Engineer

# Three Ways Graphs Enrich ML/AI

## 1. Graph Algorithms as Unsupervised Learning

!!! info
    Take a deeper look into TigerGraph's [Open-Source Algorithms](https://docs.tigergraph.com/tigergraph-platform-overview/graph-algorithm-library)

=== "Overview"
    * Graph Algorithms provide specific information about a graph's structure, either globally or with respect to certain vertices.

    * Certain algorithms can be considered learning algorithms:

        * Ranking
        * Community Detection
        * Frequent Pattern Discovery


    * The computational requirements can be intense:
      
        * Consider the theoretical memory and CPU demands (big O).
        * Consider the parallelism and programmability of the graph platform.


=== "Types of Graph Algorithms"

    **Search**

    **Path Finding**

    **Clustering / Community Detection**

      * Lenient clustering - connected component: one connection
      * Strict clustering - clique detection: every possible connection
      * Relative density - more connections in-group than between-group

    **Ranking and Centrality**

      * PageRank, HITS
      * SimRank, RoleSim

    **Frequent Pattern Discovery**

      * Agglomerative search

=== "Practical Graph Algorithm Computation"

    *Problem* - Time Complexity, basic implementation

    *Weighted Shortest Path* - O(V^2)

    *PageRank* - O(E*k), k = num of iterations

    *Closeness Centrality* - O(E*k), k = num of iterations

    *Betweenness Centrality* -O(E*V) unweighted graph, O(V^3) weighted, dense graph

    !!! note
        * E is between V and V2, depending on graph's density
        * If your graph is HUGE, then O(V3) or O(E2) might not be reasonable.
        * Use the fastest algorithms
        * Use the best implementations and platform:
            * Massively Parallel Processing
            * Highly programmable
                * Data structures
                * Control flow
                * User-customizable

!!! tip

    **Want Hands On?**

    Learn how you can implement the same techniques in your next project by checking out sample projects that use [Graph Algorithms as Unsupervised Learning](#)

## 2. Running targeted queries as Feature Extraction, leading to Explainable AI

**Graph Feature Extraction & Explainable AI**

With having a data model, the graph itself is explanatory which is sometimes called "Graph Analytics" = Connecting the Dots


![explain-ai-graph](/assets/images/explain-ai-graph.png)

**Detecting Phone-Based Fraud by Analyzing Network or Graph Relationship Features**

![good-bad-phone](/assets/images/gPhone-bPhone.png)

Model is a weighted sum of graph features

*Example:*

  * 30% Low call back phone
  * 20% No status group
  * 15% Short calls
  * 15% Many in-group connections
  * 10% 3-step friend relation

"These are the factors that lead to phone fraud."


Graph features can be both semantically meaning AND predictive

## 3. Learning from the Graph's structure and labels for Supervised Learning

**Graph Embedding**

Constructing a feature vector representation (embedding) for the nodes of a graph.

Similar Features = Similar Structural Neighborhoods

Node2Vec is a random-walk based graph embedding framework.

1. Nodes from the same network community should have lots of interconnections.

2. Nodes that share similar roles should have similar features.

