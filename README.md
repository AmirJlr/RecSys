# RecSys
# 🎯 Recommender Systems Learning Project

> Exploring modern recommendation algorithms through two powerful approaches

[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)](https://tensorflow.org/recommenders)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)](https://pytorch-geometric.readthedocs.io/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)](https://python.org)

## 📋 Overview

This repository contains implementations and experiments with two cutting-edge approaches to recommender systems:

1. **🧠 TensorFlow Recommenders** - Deep learning-based recommendation models
2. **🔗 Link Prediction with PyTorch Geometric** - Graph neural network approaches

## 🚀 Approaches

### 1. TensorFlow Recommenders (TFRS)
- **Collaborative Filtering**: User-item interaction modeling
- **Content-Based Filtering**: Feature-rich recommendation models
- **Deep & Wide Models**: Combined memorization and generalization
- **Sequential Models**: Time-aware recommendations

### 2. Link Prediction with PyTorch Geometric
- **Graph Neural Networks**: Node embedding learning
- **Graph Convolutional Networks (GCN)**: Localized feature aggregation
- **Graph Attention Networks (GAT)**: Attention-based node interactions
- **Knowledge Graph Embeddings**: Complex relationship modeling

## 📁 Project Structure

```
📦 recommender-systems-learning
│
├── 📂 tensorflow-recommenders/
│   
├── 📂 pytorch-geometric/  
│
├── 📂 datasets/

```

## 🛠️ Installation

### Prerequisites
- Python 3.8+
- CUDA-compatible GPU (recommended)



### Dependencies

```bash
# TensorFlow Recommenders
pip install tensorflow-recommenders
pip install tensorflow

# PyTorch Geometric
pip install torch torchvision torchaudio
pip install torch-geometric
pip install pyg-lib torch-scatter torch-sparse -f https://data.pyg.org/whl/torch-2.0.0+cu118.html
```

## 📊 Datasets

- **MovieLens**: Movie rating predictions
- **Amazon Product Data**: Product recommendations
- **Citation Networks**: Academic paper recommendations
- **Social Networks**: Friend/connection prediction

## 🎯 Key Learning Objectives

### TensorFlow Recommenders
- [ ] Build matrix factorization models
- [ ] Implement deep neural collaborative filtering
- [ ] Create hybrid recommendation systems
- [ ] Handle cold start problems
- [ ] Optimize for scalability

### PyTorch Geometric
- [ ] Understand graph-based recommendations
- [ ] Implement node embedding techniques
- [ ] Build link prediction models
- [ ] Explore attention mechanisms in graphs
- [ ] Apply to knowledge graph completion




## 📚 Resources & References

### TensorFlow Recommenders
- [Official Documentation](https://www.tensorflow.org/recommenders)
- [TFX Tutorials](https://www.tensorflow.org/recommenders/examples)
- [Research Papers](https://research.google/pubs/?area=machine-learning)

### PyTorch Geometric
- [Official Documentation](https://pytorch-geometric.readthedocs.io/)
- [Graph ML Papers](https://github.com/thunlp/GNNPapers)
- [Geometric Deep Learning](https://geometricdeeplearning.com/)

## 🤝 Contributing

Feel free to contribute by:
- Adding new model implementations
- Improving existing code
- Adding comprehensive documentation
- Reporting issues and bugs


## 🙏 Acknowledgments

- TensorFlow Recommenders team for the amazing framework
- PyTorch Geometric community for graph ML tools
- Open source datasets contributors

---

<div align="center">
  <strong>Happy Learning! 🎓</strong>
  <br>
  <em>Building the future of personalized recommendations</em>
</div> 
