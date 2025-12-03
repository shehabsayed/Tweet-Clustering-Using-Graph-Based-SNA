# Tweet-Clustering-Using-Graph-Based-SNA

This notebook analyzes 1,530 tweets collected during the “#Clasico” match to identify sub-events within the game. After cleaning and exploring the dataset, tweets are modeled as a graph where edges represent similarity based on text content and temporal proximity.

Multiple clustering techniques are applied, including K-core clustering (K = 5, min_common = 3) and two additional clustering algorithms. The results are compared to determine which method best captures meaningful match sub-stories such as goals, fouls, or penalties.

The notebook is structured to follow the full assignment workflow: data preparation, graph construction, clustering, and final analysis.
