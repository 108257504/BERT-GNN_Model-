---
marp: true
---

# Urban Functional Area Identification in Shanghai

This project implements a novel framework for identifying urban functional areas in Shanghai using the BERT-GNN model with Points of Interest (POI) data. The BERT-GNN model integrates the Bidirectional Encoder Representations from Transformers (BERT) with Graph Neural Networks (GNN) to generate comprehensive representations of urban areas considering both functional and spatial contexts.

## Project Structure

The project directory contains the following files:

- `random_id_type_seq_BLOCK_ID_model_0.model`: Model file for the BERT-GNN model.
- `random_id_type_seq_BLOCK_ID_0.pkl`: Pickle file containing the preprocessed POI data.
- `cluster_poi_type.pkl`: Pickle file containing the clustered POI types.
- `shequ_poi.pkl`: Pickle file with POI data at the community (shequ) level.
- `shequ_cluster_df (1).pkl`: Pickle file containing the clustered community data.
- `shequ_cluster_df (1).shp`: Shapefile for the clustered community data.
- `identify_functional_areas.ipynb`: Jupyter Notebook for identifying functional areas.
- `shequ_cluster_map.png`: Additional image file for the clustered community map.
- `shequ_cluster_map_k8.png`: Additional image file for the clustered community map with K=8.
- `shequ_cluster_df.pkl`: Pickle file for the clustered community data.
- `shequ_cluster_df.shp`: Shapefile for the clustered community data.
- `areas_annotation.ipynb`: Jupyter Notebook for annotating functional areas.
- `shequ_cluster_df (1).cpg`: Codepage file for the clustered community shapefile.
- `shequ_cluster_df (1).dbf`: Database file for the clustered community shapefile.
- `shequ_cluster_df (1).prj`: Projection file for the clustered community shapefile.
- `shequ_cluster_df (1).shx`: Shape index file for the clustered community shapefile.

## Usage

1. Install the required dependencies.
2. Run the Jupyter Notebooks in the following order:
   - `identify_functional_areas.ipynb`: Identifies the functional areas using the BERT-GNN model.
   - `functional_areas_annotation.ipynb`: Annotates the identified functional areas.
3. Analyze the results and generated visualizations.

## Dependencies

- Python 3.12
- PyTorch
- NetworkX
- Geopandas
- Matplotlib
- Shapely.
# BERT-GNN_Model-
