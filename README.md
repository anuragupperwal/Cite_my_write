# Citation Network Link Prediction Using Graph Neural Networks

## Project Description

This project focuses on predicting citation links in academic papers using Graph Neural Networks (GNNs). By constructing and analyzing a citation network where nodes represent papers and edges represent citations, the model predicts potential future citations by leveraging node features and the graph structure.

## Technologies Used

- **Programming Language**: Python
- **Frameworks and Libraries**:
  - PyTorch
  - PyTorch Geometric
  - NetworkX (for graph manipulation)
  - Plotly (for interactive 3D visualization)
  - Scikit-learn (for data preprocessing and evaluation)
- **Graph Neural Network Models**:
  - Graph Convolutional Network (GCN)
  - GraphSAGE

## Key Features

- **Graph Neural Network Architecture**:
  - Designed and implemented GCN and GraphSAGE models for link prediction.
- **Data Preprocessing**:
  - Processed the Cora citation dataset, extracted features, and constructed the adjacency matrix.
- **Custom Functions**:
  - Developed custom functions to handle dynamic graph structures for link prediction.
- **Model Training and Optimization**:
  - Conducted model training and hyperparameter tuning to optimize performance.
- **Visualization**:
  - Visualized the citation network and prediction results using interactive 3D plots.

## How It Works

1. **Data Preparation**:
   - The Cora citation dataset is preprocessed to create a feature matrix and adjacency matrix representing the citation network.
2. **Model Implementation**:
   - Implemented GCN and GraphSAGE architectures using PyTorch and PyTorch Geometric.
3. **Training and Evaluation**:
   - Trained the models on the preprocessed dataset and evaluated their performance on link prediction tasks.
4. **Visualization**:
   - Used NetworkX and Plotly to create interactive 3D visualizations of the citation network and prediction results.

## Usage

Since this project is contained within a Jupyter Notebook (`.ipynb`), you can directly open and run the notebook to explore the data preprocessing steps, model implementation, training, and visualization.

## Results and Impact

- **Accuracy**:
  - Achieved high accuracy in predicting citation links, demonstrating the effectiveness of GNNs for link prediction tasks.
- **Applications**:
  - The model's predictions provide insights into potential future citations, which can be valuable for academic recommendation systems and research impact analysis.

## Author

- **Anurag Upperwal**: 
- Email: anuragupperwal@gmail.com


## Acknowledgments

- This project uses the Cora citation dataset.
- The implementation leverages the PyTorch Geometric library for GNN operations.
