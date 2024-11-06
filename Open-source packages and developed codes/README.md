<ul>
    <li><a href="#Tools for air quality data analysis">Tools for air quality data analysis</a></li>
    <li><a href="#Popular packages">Popular packages</a></li>
    <li><a href="#POI factors">POI factors</a></li>
    <li><a href="#Traffic factors">Traffic factors</a></li>
    
</ul>

<h2 id="Tools for air quality data analysis">🔧 Tools for air quality data analysis</h2>

Openair: Tools for the Analysis of Air Pollution Data

Openair is an R package developed for the purpose of analysing air quality data — or more generally atmospheric composition data. The package is extensively used in academia, the public and private sectors. The project was initially funded by the UK Natural Environment Research Council (NERC), with additional funds from the UK Department for Environment Food & Rural Affairs (Defra).

- [Openair](https://github.com/davidcarslaw/openair)
- [Openair](https://cran.r-project.org/web/packages/openair/index.html)

---

GNNkeras: A Keras-based library for Graph Neural Networks and homogeneous and heterogeneous graph processing

GNNkeras is a Keras-based library designed for implementing various Graph Neural Networks (GNNs). It supports the classification and clustering of nodes, edges, or entire graphs and is applicable to both homogeneous and heterogeneous graphs. GNNkeras utilizes inductive and mixed inductive–transductive learning and includes a layered GNN model known as LGNN.
This library provides valuable insights for clustering air quality monitoring stations and is also highly useful for implementing Graph Convolutional Networks (GCNs).

- [GNNkeras](https://github.com/ElsevierSoftwareX/SOFTX-D-22-00019)
- [Paper link](https://www.sciencedirect.com/science/article/pii/S2352711022000486)

---

SpatialCluster: A Python library for urban clustering

SpatialCluster is a Python library for clustering urban areas with geolocated data. It integrates methods like Deep Modularity Networks, Gaussian Mixtures, and K-Nearest Neighbors, with evaluation metrics such as Adjusted Rand Index. The library offers map visualization features and accessible documentation, supporting researchers and urban planners in urban data analysis.
This library can provide ideas for clustering air quality monitoring stations.

- [SpatialCluster](https://github.com/ElsevierSoftwareX/SOFTX-D-24-00008)
- [Paper link](https://github.com/ElsevierSoftwareX/SOFTX-D-24-00008)

---

SimilarityTS: Toolkit for the evaluation of similarity for multivariate time series

SimilarityTS is a toolkit for evaluating similarity in multivariate time series using metrics such as Kullback–Leibler divergence, Dynamic Time Warping, PCA, and t-SNE. It standardizes comparison methods and enhances experiment reproducibility.
This library can be utilized for clustering time series data from air quality monitoring stations, offering innovative insights and fresh ideas.

- [SimilarityTS](https://github.com/ElsevierSoftwareX/SOFTX-D-23-00469)
- [Paper link](https://www.sciencedirect.com/science/article/pii/S2352711023002236)

---

Space Time Cube analytics in QGIS and Python for hot spot detection

A QGIS plugin and a Python package are presented for hot spot detection in space-time point data from GNSS receivers. By aggregating data into a Space Time Cube (STC) and applying statistical methods like Getis–Ord or local Moran’s I, users can identify localized clusters. The QGIS plugin features a user-friendly GUI, while the Python package is designed for sensitivity analysis. Experiments with New York City taxi data reveal that detected hot spots vary based on passenger weighting and the chosen statistical method, contributing to open-source geospatial tools for diverse applications.
This package can similarly be used for space-time pollution data to identify hot spots.

- [Space Time Cube analytics in QGIS and Python for hot spot detection](https://github.com/ElsevierSoftwareX/SOFTX-D-22-00425)
- [Paper link](https://www.sciencedirect.com/science/article/pii/S2352711023001942)

<h2 id="Popular packages">📦 Popular packages</h2>

PyTorch Geometric (PyG)

PyG (PyTorch Geometric) is a library that extends PyTorch, providing a user-friendly platform for writing and training Graph Neural Networks (GNNs) across various applications involving structured data.

The library offers numerous techniques for deep learning on graphs and other irregular structures, collectively referred to as geometric deep learning, derived from a range of published research. Additionally, PyG includes convenient mini-batch loaders that facilitate operations on multiple small graphs or a single large graph, supports multi-GPU setups, integrates with torch.compile, and is compatible with DataPipe. It also features a wide selection of commonly used benchmark datasets, allowing users to easily create their own datasets through straightforward interfaces. Furthermore, it provides useful transformations for learning on arbitrary graphs as well as for working with 3D meshes or point clouds.

- [PyG](https://pyg.org/)
- [PyG](https://github.com/pyg-team/pytorch_geometric)

---

Pytorch Geometric Temporal

PyTorch Geometric Temporal is an extension library for PyTorch Geometric, specifically designed for temporal graph neural networks. It leverages open-source deep learning and graph processing frameworks to facilitate the processing of spatio-temporal signals using advanced deep learning and parametric learning techniques. As the first open-source library dedicated to temporal deep learning on geometric structures, it offers constant-time difference graph neural networks for both dynamic and static graphs, utilizing discrete time graph snapshots for implementation.

The methods included in this library are drawn from a wide range of prestigious conferences and workshops in data mining (such as WWW and KDD) and artificial intelligence and machine learning (including AAAI, ICONIP, and ICLR), as well as contributions from leading journals.

- [Pytorch Geometric Temporal](https://pytorch-geometric-temporal.readthedocs.io/en/latest/)
- [Pytorch Geometric Temporal](https://github.com/benedekrozemberczki/pytorch_geometric_temporal)

---

Torch Spatiotemporal (TSL)

Tsl (Torch Spatiotemporal Library) is a Python library designed for the neural processing of spatiotemporal data, specifically focusing on Graph Neural Networks.

Built on the most widely used libraries within the Python scientific computing ecosystem, Tsl aims to provide a streamlined workflow that encompasses everything from data preprocessing to model prototyping. Notably, Tsl offers a comprehensive set of utilities for developing neural networks using PyTorch and PyTorch Geometric (PyG) to effectively process spatiotemporal data signals.

- [tsl](https://torch-spatiotemporal.readthedocs.io/en/latest/)
- [tsl](https://github.com/TorchSpatiotemporal/tsl)

---

Deep Graph Library (DGL)

In recent years, deep learning has made significant strides in areas like image recognition, machine translation, and game playing, primarily through techniques such as convolution, attention, and recurrence. These methods often depend on the correlations in data, with CNNs focusing on spatial relationships and RNNs on sequential data.

Research is increasingly exploring graph-structured data, addressing challenges in social networks and recommender systems, where interactions between entities can be more informative than the entities themselves. Graph neural networks are also being applied to images, text, and games, allowing various data structures to be represented as graphs.

To support this trend, the Deep Graph Library (DGL) was created to simplify the implementation of graph neural networks and facilitate integration with tensor-based frameworks like PyTorch and MXNet.

- [DGL](https://www.dgl.ai/)
- [DGL](https://github.com/dmlc/dgl/)

---

Paddle Graph Learning (PGL) 

Paddle Graph Learning (PGL) is a powerful framework for graph learning built on PaddlePaddle, an open-source deep learning platform by Baidu. It is optimized for efficient processing of large-scale graphs, enabling quick computations and minimal memory usage. PGL offers flexibility, allowing researchers to implement a wide variety of graph algorithms and machine learning techniques, including Graph Neural Networks (GNNs). The framework provides a rich library of pre-implemented models for tasks such as node classification and link prediction, along with user-friendly APIs that facilitate easy experimentation. It supports diverse graph data types, including directed, undirected, weighted, and dynamic graphs, making it applicable across various domains like social network analysis and recommendation systems. With strong community support and comprehensive documentation, PGL empowers users to effectively leverage graph-structured data in their projects.

- [PGL](https://pgl.readthedocs.io/en/latest/)
- [PGL](https://github.com/PaddlePaddle/PGL)

---

Spektral

Spektral is a Python library built on TensorFlow and Keras, designed for deep learning on graph-structured data. It provides a user-friendly interface for implementing and training various Graph Neural Networks (GNNs), including Graph Convolutional Networks (GCNs) and Graph Attention Networks (GATs). The library features utilities for data preprocessing, enabling users to easily handle graph data and load standard datasets. Spektral supports dynamic graphs and incorporates temporal aspects, making it suitable for applications like social network analysis and molecular graph analysis. With an active community and comprehensive tutorials, Spektral is accessible to both beginners and experienced practitioners in the field of graph deep learning.

- [Spektral](https://graphneural.network/)
- [Spektral](https://github.com/danielegrattarola/spektral/)

---

Jraph - A library for graph neural networks in jax

Jraph is a library for graph neural networks (GNNs) built on JAX, designed for ease of use and flexibility in implementing deep learning models on graph data. It provides a simple API that allows users to quickly create various types of GNNs, such as Graph Convolutional Networks (GCNs) and Graph Attention Networks (GATs). Leveraging JAX's capabilities, Jraph ensures efficient computations through Just-In-Time (JIT) compilation. The library supports integration with other JAX tools and frameworks, making it suitable for a range of applications, including social network analysis and anomaly detection. Overall, Jraph is a powerful tool for researchers and developers working with graph-based deep learning.

- [Jraph](https://jraph.readthedocs.io/en/latest/)
- [Jraph](https://github.com/google-deepmind/jraph)

---

StellarGraph

StellarGraph is a Python library designed for machine learning on graph-structured data, offering a wide range of graph neural network (GNN) models like Graph Convolutional Networks (GCNs) and Graph Attention Networks (GATs). It features a user-friendly API that simplifies the process of building and training GNN models, catering to both beginners and experts. The library supports various tasks, including node classification, graph classification, and link prediction. StellarGraph integrates seamlessly with popular frameworks like TensorFlow and Keras, enhancing its usability in machine learning workflows. With extensive documentation and tutorials, it serves as a valuable resource for researchers and practitioners working with graph data.

- [StellarGraph](https://stellargraph.readthedocs.io/en/stable/)
- [StellarGraph](https://github.com/stellargraph/stellargraph)

---

GraphLearn

GraphLearn is a library designed for deep learning on graph-structured data, emphasizing efficiency and scalability for large graphs. It provides tools for implementing various graph neural network (GNN) models, including Graph Convolutional Networks (GCNs) and GraphSAGE, making it suitable for applications like social network analysis and recommendation systems. The library is optimized for performance, leveraging parallel computing and memory management to enhance training speed. Fully compatible with TensorFlow, GraphLearn allows users to integrate TensorFlow’s features for model training and deployment. With comprehensive documentation and examples, it serves as a valuable resource for researchers and practitioners working with graph data.

- [GraphLearn](https://graph-learn.readthedocs.io/en/latest/)
- [GraphLearn](https://github.com/alibaba/graph-learn?tab=readme-ov-file)

---

CogDL

CogDL is a comprehensive library designed for deep learning on graphs, particularly aimed at facilitating research in graph representation learning and graph neural networks (GNNs). It offers a wide range of state-of-the-art GNN models and tools for various tasks, including node classification, link prediction, and graph classification. The library emphasizes ease of use with a user-friendly API and modular architecture, enabling researchers to quickly prototype and experiment with different algorithms. CogDL supports integration with popular machine learning frameworks like PyTorch and TensorFlow, making it versatile for different research needs. With extensive documentation and examples, CogDL provides a robust resource for researchers and practitioners in the field of graph-based deep learning.

- [CogDL](https://docs.cogdl.ai/en/latest/)
- [CogDL](https://github.com/THUDM/cogdl/blob/master/docs/source/index.rst)

---



🌫️ PM2.5-GNN




A Domain Knowledge Enhanced Graph Neural Network For PM2.5 Forecasting

- [PM2.5-GNN](https://github.com/shuowang-ai/PM2.5-GNN)

---

Forecasting using spatio-temporal data with combined Graph Convolution + LSTM model

- [Graphs with time series and sequence data](https://stellargraph.readthedocs.io/en/stable/demos/time-series/gcn-lstm-time-series.html)

---

Air Quality Prediction

BLG556E - Digital Solution for Smart Cities (AirQualityPrediction)

- [GCN-LSTM](https://github.com/kadirkaynak/air-quality-prediction)

---

Graph-based Neural Networks

This page is to summarize important materials about graph-based neural networks and relational networks.

- [Graph-based Neural Networks](https://github.com/sungyongs/graph-based-nn)

---

Graph Convolutional Networks

Implementation of Graph Convolutional Networks in TensorFlow

- [GCN](https://github.com/sungyongs/gcn)

---

Differentiable Physics-informed Graph Networks

- [DPGN](https://github.com/sungyongs/dpgn)

---

Sparse Graph Learning from Spatiotemporal Time Series (JMLR 2023)

- [](https://github.com/andreacini/sparse-graph-learning)

---

Graph WaveNet for Deep Spatial-Temporal Graph Modeling

- [](https://github.com/nnzhan/Graph-WaveNet)

---

Spatio-Temporal Graph Convolutional Networks

- [](https://github.com/hazdzz/STGCN)

---

Deep Learning Models

- [](https://github.com/SubhojitMandal-iiits/deeplearning-models)

---

ASTGNN

- [](https://github.com/SubhojitMandal-iiits/ASTGNN)

---

Spatial Temporal Graph Convolutional Networks (ST-GCN)

- [](https://github.com/wanjinchang/st-gcn)

---

T-GCN

This repository includes our works on Graph representation learning and its application on Traffic Flow Prediction.

- [T-GCN](https://github.com/lehaifeng/T-GCN/tree/master)

---

Awesome Graph Neural Networks for Time Series Analysis (GNN4TS)

- [](https://github.com/KimMeen/Awesome-GNN4TS)

GNNkeras: A Keras-based library for Graph Neural Networks and homogeneous and heterogeneous graph processing

https://github.com/SoftwareImpacts/SIMPAC-2021-57

https://github.com/mdeff/cnn_graph

<h2 id="tools">📦 Tools</h2>

* [Pytorch Geometric](https://pytorch-geometric.readthedocs.io/en/latest/)
* [Pytorch Geometric Temporal](https://pytorch-geometric-temporal.readthedocs.io/en/latest/notes/introduction.html)
* [Deep Graph Library](https://www.dgl.ai/)
* [Stellar Graph](https://stellargraph.readthedocs.io/en/stable/)
* [GNNLens](https://github.com/dmlc/GNNLens2)
* [GraphVite](https://graphvite.io/)
* [jraph](https://github.com/google-deepmind/jraph)
* [Spektral](https://graphneural.network/)
* [Keras Graph Convolutions](https://github.com/SoftwareImpacts/SIMPAC-2021-57)
* [Graph Convolutional Networks](https://github.com/tkipf/gcn)
* [Convolutional Neural Networks on Graphs with Fast Localized Spectral Filtering](https://github.com/mdeff/cnn_graph)


