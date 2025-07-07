# graph_analysis.py
Graph
from degano import GraphAnalyzer

# Load pre-built Twitter graph
analyzer = GraphAnalyzer("twitter_graph.json")

# Detect suspicious clusters
clusters = analyzer.detect_fake_clusters()

# Show visual graph
analyzer.visualize_clusters()
