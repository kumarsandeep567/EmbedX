# EmbedX: Multi-lingual Embedding Model

## Project Overview
- EmbedX is an Natural Language Processing project focused on developing and comparing different word embedding approaches across multiple languages. 
- The project aims to evaluate the effectiveness of various embedding techniques through practical applications in chatbot development and comprehensive comparative analysis.

## Key Components of this project
- **Part 1.** Multi-lingual Word2Vec Implementation
    - Focus on creating a model to produce Word2Vec embeddings for non-English languages.

- **Part 2.** RNN-based Embedding Architecture 
    - Development of a custom RNN architecture for embedding generation. 
    - Comparative analysis against standard Keras Word2Vec embeddings.

- **Part 3.** Chatbot Integration & Evaluation 
    - Development of an embedding-powered chatbot system.
    - Comparative testing between English and non-English embedding models
    - Performance benchmarking across different embedding sources

- **Part 4.** Embedding Quality Assessment
    - Comparative analysis of Word2Vec and RNN-based approaches
    - Implementation of multiple evaluation metrics

- **Part 5.** DNN Comparative Study
    - Implementation of a shallow DNN for embedding generation
    - Head-to-head comparison with RNN-based embeddings

## Priority Focus
- The core focus is on developing and optimizing the RNN-based embedding architecture, as this forms the foundation for subsequent comparative analyses and applications.

## Features
- Multi-lingual Word2Vec embeddings training
- Custom RNN-based embedding architecture
- Chatbot implementation with embedding integration
- Comparative analysis framework for embedding quality
- DNN-based embedding generation and evaluation
- Support for pre-trained embedding integration

## Setup Instructions

- Clone the repository and navigate to it:
   ```bash
   git clone https://github.com/kumarsandeep567/EmbedX.git

   cd EmbedX
   ```

- Please install the dependencies by running 
   ```bash
   pip install -r requirements.txt
   ```

- **Installing TensorFlow** : To ensure you install the correct version of TensorFlow, please refer to TensorFlow's official installation guide [here](https://www.tensorflow.org/install/pip)

## Acknowledgments
- Tomas Mikolov, Greg Corrado, Kai Chen, Jeffrey Dean (Google) - [Efficient Estimation of Word Representations in Vector Space](https://arxiv.org/pdf/1301.3781)