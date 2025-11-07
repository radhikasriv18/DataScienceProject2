# CS 6010 Data science programming Project 2

This project contains analysis of two different types of networks:

For each dataset we calculated five graph properties (degree distribution, clustering coefficient, diameter, average shortest path length, and assortativity) to help characterize the network structure.

1. **Facebook Social Network Analysis** (`facebook_social_network_analysis.ipynb`)

   - Analysis of social connections in Facebook network data
   - Uses the dataset from `facebook_combined.txt`
   - Explores social network properties and metrics

2. **Texas Road Network Analysis** (`texas_road_network_analysis.ipynb`)
   - Analysis of the Texas road network infrastructure
   - Uses the dataset from `roadNet-TX.txt`
   - Examines road network characteristics and connectivity

## Datasets

The dataset files are not included in this repository. Download them from the Stanford Network Analysis Project (SNAP) and place the extracted `.txt` files in the project root (or update the paths in the notebooks).

- Facebook social network (`facebook_combined.txt`)

  - Dataset page: https://snap.stanford.edu/data/egonets-Facebook.html
  - Direct download (compressed): https://snap.stanford.edu/data/facebook_combined.txt.gz

- Texas road network (`roadNet-TX.txt`)
  - Dataset page: https://snap.stanford.edu/data/roadNet-TX.html
  - Direct download (compressed): https://snap.stanford.edu/data/roadNet-TX.txt.gz

## Files

- `facebook_social_network_analysis.ipynb`: Jupyter notebook containing the analysis of Facebook social network
- `texas_road_network_analysis.ipynb`: Jupyter notebook containing the analysis of Texas road network

## Getting Started

To run the analysis:

1. Ensure you have Jupyter Notebook installed
2. Download the required datasets (see the "Datasets" section) and extract them if necessary. If you downloaded the `.txt.gz` files, decompress them (for example, using a tool that supports gzip) to obtain `facebook_combined.txt` and `roadNet-TX.txt`.
3. Place the extracted `.txt` files in the project root (same folder as the notebooks), or update the file paths in the notebooks if you prefer a different location.

Note: The notebooks expect the datasets to be accessible via the filenames above by default. If you move files, open the notebook and modify the file path strings where the data is loaded.
