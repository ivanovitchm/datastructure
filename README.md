
<center><img width="800" src="images/ct.jpeg"></center>

# Federal University of Rio Grande do Norte
## Technology Center
### Department of Computer Engineering and Automation 
#### Algorithms and Data Structure II (DCA3702)

This is the repository for the Algorithms and Data Structures II course, offered by the Department of Computer Engineering and Automation ([DCA](https://www.dca.ufrn.br)) of the Technology Center ([CT](https://www.ct.ufrn.br/)) at the Federal University of Rio Grande do Norte ([UFRN](https://www.ufrn.br)).

The DCA aims to train professionals capable of designing and developing computer systems for industrial automation, embedded systems, software systems, distributed systems, computer networks, and information systems. The CT offers undergraduate and graduate courses in Engineering. This course is part of the curriculum of the Computer Engineering program at DCA/UFRN.


#### References

- :books: [Coscia, Michele. The Atlas for the Aspiring Network Scientist](https://www.networkatlas.eu/)
- :books: [Newman, Mark. Networks](https://global.oup.com/academic/product/networks-9780198805090?cc=br&lang=en&)


| Tool | Link |
|------|------|
| :smiley: Networkx | [networkx.org](https://networkx.org/) |
| :gear: Gephi | [gephi.org](https://gephi.org/) |
| :rocket: OSMnx | [github.com/gboeing/osmnx](https://github.com/gboeing/osmnx) |
| :floppy_disk: Dataset | [snap.stanford.edu/data](https://snap.stanford.edu/data/) |


### Lessons

**Week 01**
- [![Open in PDF](https://img.shields.io/badge/-PDF-EC1C24?style=flat-square&logo=adobeacrobatreader)](https://github.com/ivanovitchm/datastructure/tree/main/lessons/week01/lesson01.pdf) **Course Outline:** Provides an overview of the course structure and topics covered.
    -  🎉 GitHub Education Benefits
        - GitHub Education Pro: Get access to the GitHub Education Pro pack by visiting [GitHub Education](https://education.github.com/pack)
    - 📖 Learning Resources 
        - GitHub Learning Game: Check out the interactive Git learning game at [GitHub Learning Game](https://learngitbranching.js.org/)

**Week 02**
- [![Open in PDF](https://img.shields.io/badge/-PDF-EC1C24?style=flat-square&logo=adobeacrobatreader)](https://github.com/ivanovitchm/datastructure/blob/main/lessons/week02/lesson02.pdf) **From Real-World Systems to Networks**: Learn how real-world systems can be modeled as networks. We introduce the basic elements of a graph, explore different types of networks, and discuss applications involving social networks, transportation, temporal networks, and knowledge graphs.
    - [![Jupyter](https://img.shields.io/badge/-Notebook-191A1B?style=flat-square&logo=jupyter)](https://github.com/ivanovitchm/datastructure/blob/main/lessons/week02/NetworkElements01.ipynb) **Hands-on — Modeling Networks with NetworkX**: Build, inspect, and manipulate graphs in Python. Practice graph representations, node and edge attributes, directed graphs, multigraphs, degree and neighborhood analysis, connectivity, and modeling decisions through guided examples and exercises.
    - :books: **Further Reading & Practice**:
        - Chapters 2, 3, 6, and 7 of [The Atlas for the Aspiring Network Scientist](https://www.networkatlas.eu/).
        - [NetworkX Documentation](https://networkx.org/)
- [![Open in PDF](https://img.shields.io/badge/-PDF-EC1C24?style=flat-square&logo=adobeacrobatreader)](https://github.com/ivanovitchm/datastructure/blob/main/lessons/week02/lesson03.pdf) **Network Fundamentals II**: Extended graphs, density and sparsity, subnetworks, degree, degree distribution, and network representation.
    - [![Jupyter](https://img.shields.io/badge/-Notebook-191A1B?style=flat-square&logo=jupyter)](https://github.com/ivanovitchm/datastructure/blob/main/lessons/week02/lesson03.ipynb) Exploring graph types, multilayer networks, density, subnetworks, degree, and adjacency matrices using NetworkX.
    - :books: Further reading: chapters 7, 8, and 9 of the book [The Atlas For The Aspiring Network Scientist](https://www.networkatlas.eu/).

**Week 03**
- [![Open in PDF](https://img.shields.io/badge/-PDF-EC1C24?style=flat-square&logo=adobeacrobatreader)](https://github.com/ivanovitchm/datastructure/blob/main/lessons/week03/lesson04.pdf) **Small-World Networks and Graph Traversal**: Introduction to the small-world phenomenon through classical examples such as Milgram's experiment, the Erdős number, and the Oracle of Bacon. The lecture connects these concepts to graph traversal and shortest-path reasoning, with particular emphasis on Breadth-First Search (BFS) and Depth-First Search (DFS).
    - **Case Study — Wikipedia Network:** Construction and structural analysis of a directed network of Wikipedia pages using a snowball sampling strategy.
        - Compare BFS and DFS in terms of exploration strategy, frontier size, memory requirements, and path discovery.
        - Construct a directed network from Wikipedia pages starting from a predefined seed node.
        - Collect pages through a BFS-based snowball sampling process and analyze the growth of successive network layers.
        - Preprocess the network by handling duplicate nodes, self-loops, and sampling artifacts.
        - Examine the degree distribution and distinguish the network core from its low-degree fringe.
        - Analyze node relevance through indegree and outdegree and discuss the impact of the sampling strategy on the observed network structure.
        - [![Jupyter](https://img.shields.io/badge/-Notebook-191A1B?style=flat-square&logo=jupyter)](https://github.com/ivanovitchm/datastructure/blob/main/lessons/week03/wikipedia.ipynb) **Wikipedia Network — BFS-Based Sampling and Structural Analysis**

**Week 04**
- [![Open in PDF](https://img.shields.io/badge/-PDF-EC1C24?style=flat-square&logo=adobeacrobatreader)](https://github.com/ivanovitchm/datastructure/blob/main/lessons/week04/lesson05.pdf) **Network Navigation and Local Structure**: This lesson moves beyond graph representation to explore how nodes can be reached, how distances are measured, how connected regions emerge, and how local relationships form triangles and clusters.
    - [![Jupyter](https://img.shields.io/badge/-Notebook-191A1B?style=flat-square&logo=jupyter)](https://github.com/ivanovitchm/datastructure/blob/main/lessons/week04/practice.ipynb) **Hands-on — Paths, Components, and Clustering**
        - Walks, trails, paths, and powers of the adjacency matrix
        - Shortest paths in directed, undirected, weighted, and unweighted networks
        - Average shortest-path length, diameter, and global efficiency
        - Connected components and the Giant Connected Component (GCC)
        - Weakly and Strongly Connected Components (WCC and SCC)
        - Triangles, clustering coefficient, and the friend-of-a-friend principle
        - Practical applications using NetworkX and real-world network examples
    - [![Jupyter](https://img.shields.io/badge/-Notebook-191A1B?style=flat-square&logo=jupyter)](https://github.com/ivanovitchm/datastructure/blob/main/lessons/week04/dataviz.ipynb) **Advanced Network Visualization with nxviz**
        - The nxviz grammar: node tables, edge tables, grouping, sorting, and visual encodings
        - Arc, Circos, Matrix, Hive, and geographic plots
        - Mapping node and edge attributes to color, size, transparency, and line width
        - Revealing communities, hubs, bridges, and structural patterns
        - Combining nxviz layouts with Matplotlib and Plotly
        - Designing deterministic and publication-ready network visualizations
- [![Open in PDF](https://img.shields.io/badge/-PDF-EC1C24?style=flat-square&logo=adobeacrobatreader)](https://github.com/ivanovitchm/datastructure/blob/main/lessons/week04/lesson06.pdf) **Hubs and Centrality Measures**: Introduction to node importance in networks through eccentricity, diameter, radius, center, and classical centrality measures such as degree, closeness, betweenness, and eigenvector centrality. 
    - [![Jupyter](https://img.shields.io/badge/-Notebook-191A1B?style=flat-square&logo=jupyter)](https://github.com/ivanovitchm/datastructure/blob/main/lessons/week04/hubs.ipynb) **Hands-on — Hubs and Centrality Analysis**
        - Compute and compare centrality measures with NetworkX
        - Analyze centrality distributions and node rankings
        - Explore the structural role of hubs in real-world networks

**Week 05**
- [![Open in PDF](https://img.shields.io/badge/-PDF-EC1C24?style=flat-square&logo=adobeacrobatreader)](https://github.com/ivanovitchm/datastructure/blob/main/lessons/week05/lesson07.pdf) **Hubs (cont.) - Core Decomposition**: Move beyond degree-based notions of importance and explore the internal organization of networks through k-core decomposition. Introduce k-core, k-shell, core number, degeneracy, and the idea of recursively peeling a network to reveal its structural core.
    - [![Jupyter](https://img.shields.io/badge/-Notebook-191A1B?style=flat-square&logo=jupyter)](https://github.com/ivanovitchm/datastructure/blob/main/lessons/week05/lesson07.ipynb) **Hands-on — Core Decomposition with NetworkX**:
        - Reconstruct and progressively peel a network to understand how k-cores and k-shells emerge
        - Compute and interpret `core_number`, `k_core`, `k_shell`, `k_crust`, `k_corona`, `onion_layers`, and `k_truss`.
        - Compare node degree with core membership and investigate why hubs are not necessarily part of the innermost core.
        - Apply core decomposition to a real-world SocioPatterns contact network and identify its innermost core.
        - Analyze degree, centrality distributions, empirical CDFs, and bivariate relationships across different k-shells.
        - Explore scientific collaboration networks and investigate how researchers are organized across structural layers.
    - [![Jupyter](https://img.shields.io/badge/-Notebook-191A1B?style=flat-square&logo=jupyter)](https://github.com/ivanovitchm/datastructure/blob/main/lessons/week05/case_study.ipynb) **Case Study**: software maintenance.
- Gephi: The Open Graph Viz Platform
    - A brief overview about Gephi  [![Open in Loom](https://img.shields.io/badge/-Video-83DA77?style=flat-square&logo=loom)](https://www.loom.com/share/6d7f83dfc4f84b66abb8690288732094?sid=6a4fa5a6-0156-49b2-b9b5-def3ae749a8e)
    - Quick start [![Open in Loom](https://img.shields.io/badge/-Video-83DA77?style=flat-square&logo=loom)](https://www.loom.com/share/61623ee4ed9948b9a9a97ed22de6e910?sid=6fe2767d-0450-4803-aede-3db0def97b1e)
    - Using layouts [![Open in Loom](https://img.shields.io/badge/-Video-83DA77?style=flat-square&logo=loom)](https://www.loom.com/share/d2d08189c32143ebb1ea5bb612ab1a4d?sid=1560527d-04ad-401f-991e-8f6ec7017890)
    - Node and network measures [![Open in Loom](https://img.shields.io/badge/-Video-83DA77?style=flat-square&logo=loom)](https://www.loom.com/share/ca4049c9502e4c4cb3c6768323b5565f?sid=deaed86c-0481-44c2-8473-8a91a4e4d07f)
    - Visualize and filtering nodes and communities [![Open in Loom](https://img.shields.io/badge/-Video-83DA77?style=flat-square&logo=loom)](https://www.loom.com/share/3e2c90775f54419cba165e28229b3ad3?sid=d441254b-57ae-4483-9ef8-12d86bea3f85)
    - Renderize, export the network, and highlight a community [![Open in Loom](https://img.shields.io/badge/-Video-83DA77?style=flat-square&logo=loom)](https://www.loom.com/share/109e2e4a596e4ecaa723d3b225f2b0c2?sid=a62dfa83-33df-4381-8e8d-9b775be5e877)
    - Deploy the network into an HTML page [![Open in Loom](https://img.shields.io/badge/webpage-open%20here-green)]( https://ivanovitchm.github.io/netdeploy/network) [![Open in Loom](https://img.shields.io/badge/-Video-83DA77?style=flat-square&logo=loom)](https://www.loom.com/share/71a93423f50247bebae0bc3ef3b9eb28?sid=2d4cb63f-c7ad-4177-9d6e-a0e607abafde)
    - Another way to publish your network to the web using Retina and Gephisto [![Open in Loom](https://img.shields.io/badge/-Video-83DA77?style=flat-square&logo=loom)](https://www.loom.com/share/72526380751c43f98c87f95910eb35ed?sid=fbe7b938-61e9-45cb-a9a0-0ce8906f1355)


**Week 06**
- [![Open in PDF](https://img.shields.io/badge/-PDF-EC1C24?style=flat-square&logo=adobeacrobatreader)](https://github.com/ivanovitchm/datastructure/blob/main/lessons/week06/lesson08.pdf) **From Text to Networks - Named-Entity Co-occurrence**: A fourth way to build a network, from raw text. Co-occurrence networks are introduced as one-mode projections of a bipartite units × items graph, with the incidence matrix and BᵀB, the clique artifact of projections, and Jaccard normalization. Named-entity recognition (spaCy) is used strictly as a tool behind a one-function contract, and the lesson is organized around Gestalt principles (whole before parts, figure and ground, similarity, common fate).
    - [![Jupyter](https://img.shields.io/badge/-Notebook-191A1B?style=flat-square&logo=jupyter)](https://github.com/ivanovitchm/datastructure/blob/main/lessons/week06/lesson08.ipynb) **Hands-on — From Text to Networks with NetworkX and spaCy**
        - Slice, extract, link: units (chapter, paragraph, sentence, document), items (named entities), and co-occurrence as a bipartite projection, built three equivalent ways (pairs per unit, BᵀB, `bipartite.weighted_projected_graph`)
        - The window decides the network: density, clustering, components, and even which pair looks closest
        - NER as a tool with a one-function contract; what it gets wrong (sentence-initial noise, wrong types, unresolved identity) and why the network depends on spans, not on types
        - From mentions to nodes: normalization, alias dictionary, automatic sieve, and why node contraction and projection do not commute
        - **Case Study — *Dom Casmurro*** (Machado de Assis, NLTK corpus): chapters as units, weighted layout, strength vs degree, weighted betweenness, backbone by weight threshold, chapter/paragraph/sentence windows on fixed positions, the invisible first-person narrator, and what the missing edges say about the chronology
        - **Case Study — *A Semana*** (244 dated chronicles, 1892–1900): document-level bipartite graph, the clique artifact and its effect on density and k-core, count vs Jaccard weights (Jaccard as an alias detector), typed nodes (PER/LOC/ORG/MISC), yearly networks and a heatmap as a news barometer
        - Challenges: three solved (sparse BᵀB, the sentence-block window curve, swapping NER for a gazetteer) and three open (temporal character network, another novel and the narrator problem, Wikipedia with links as entity resolution)
    - :books: **Further Reading & Practice**:
        - Chapter 6 (bipartite networks and one-mode projections) of [Newman, Networks](https://global.oup.com/academic/product/networks-9780198805090?cc=br&lang=en&).
        - The chapters on bipartite networks, projections, and network backboning of [The Atlas for the Aspiring Network Scientist](https://www.networkatlas.eu/).
        - Labatut, V. and Bost, X. (2019). [Extraction and analysis of fictional character networks: a survey](https://doi.org/10.1145/3344548). *ACM Computing Surveys*, 52(5).
        - Knuth, D. E. (1993). *The Stanford GraphBase*, the source of `nx.les_miserables_graph()`.
        - [spaCy: named entities](https://spacy.io/usage/linguistic-features#named-entities) and the [NLTK `machado` corpus](https://www.nltk.org/nltk_data/) (Machado de Assis, public domain).