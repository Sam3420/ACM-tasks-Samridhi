# ACM-tasks-Samridhi
# My Machine Learning and Chatbot Projects

Welcome to my GitHub repository! This repo includes some of my exciting projects that showcase my skills in machine learning, natural language processing, and web development.

## Projects Overview

### 1. Clustering Model using `KMeans` from `sklearn.cluster`
In this project, I built a clustering model using the popular `KMeans` algorithm from the `scikit-learn` library. The objective was to group data into distinct clusters based on their similarities.

#### Features:
- Utilized `KMeans` for unsupervised learning and clustering.
- Visualized clusters with `matplotlib`.
- Optimized the number of clusters using the Elbow Method.
  
#### Key Technologies:
- Python
- `scikit-learn`
- `matplotlib`
- Jupyter Notebook

You can find the code for this project in the **Clustering_Model_KMeans** folder.

### 2. Chatbot using Hugging Face Model LLaMA 2-7B and Streamlit
I developed a chatbot using the LLaMA 2-7B model from Hugging Face, integrated with Streamlit to create an interactive user interface. The model serves responses based on user input, demonstrating the power of large language models for conversational AI.

#### Features:
- Utilized Hugging Face’s LLaMA 2-7B model for text generation.
- Built a real-time interface using Streamlit.
- Deployed the chatbot locally using Ngrok for easy sharing.

#### Key Technologies:
- Python
- Hugging Face Transformers
- LLaMA 2-7B model
- Streamlit
- Ngrok

You can find the code for this project in the **Chatbot_LLaMA2_Streamlit** folder.

## Getting Started

### Chatbot:
1. Install the necessary libraries:
   ```bash
   !pip install -qq langchain wget llama-index cohere llama-cpp-python
   !pip -q install streamlit
   !pip install pyngrok
   
