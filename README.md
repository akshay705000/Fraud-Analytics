
# Fraud Detection for Financial Dataset

### Project Duration: Jan 2024 - May 2024

This project focuses on detecting fraudulent activities in financial datasets by leveraging various graph-based and deep learning techniques. Below are the methods implemented and their purpose in identifying suspicious patterns within financial transactions.

## Techniques Applied:

### 1. Node2Vec:
- **Description**: Node2Vec is used to learn low-dimensional representations of nodes in the financial transaction network.
- **Purpose**: By generating node embeddings, we can capture the structural and relational information of nodes, aiding in the identification of anomalous or fraudulent nodes.

### 2. Spectral Clustering:
- **Description**: Spectral clustering is applied to group nodes in the financial network based on their connectivity.
- **Purpose**: This helps detect clusters of normal vs. abnormal behavior, highlighting potential fraudulent clusters of transactions.

### 3. Graph Convolutional Network (GCN):
- **Description**: GCN is implemented to capture graph-structured data and learn meaningful representations of nodes.
- **Purpose**: GCN helps in detecting fraud by aggregating information from neighboring nodes, allowing the model to identify suspicious patterns across the network.

---

## Trust Rank Algorithm:
- **Description**: Trust Rank is a node-ranking algorithm that evaluates the trustworthiness of nodes in a payment network.
- **Purpose**: It assigns a trust score to each node, which helps in detecting fraudulent entities based on their transactions and interactions.

---

## Neural Autoencoder and Variational Autoencoder (VAE) for Credit Card Fraud Detection:

### 1. Neural Autoencoder:
- **Description**: A neural autoencoder was developed to identify anomalous transactions by reconstructing normal transaction patterns and flagging deviations.
- **Purpose**: This model effectively detects fraudulent credit card transactions by learning patterns from normal transactions.

### 2. Variational Autoencoder (VAE):
- **Description**: VAE was implemented to capture the latent structure of transaction data and model uncertainty in anomaly detection.
- **Purpose**: By modeling the distribution of the data, VAE helps in distinguishing between legitimate and fraudulent transactions more robustly.

---

## Dataset:
- The project uses a financial transaction dataset containing transaction records from various users and institutions. The dataset includes normal and fraudulent transactions, providing a comprehensive environment for testing different fraud detection techniques.

---

## Results:
- **Node2Vec and Spectral Clustering**: Successfully identified clusters with a high concentration of fraudulent activities.
- **GCN**: Improved detection rates of suspicious transactions by incorporating relational data from neighboring nodes.
- **Trust Rank**: Effectively ranked nodes by trustworthiness, detecting key fraudulent nodes in the network.
- **Autoencoder & VAE**: Both models demonstrated high accuracy in detecting anomalous credit card transactions, with the VAE providing more nuanced detection capabilities.

---

## Installation:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/fraud-detection.git
   cd fraud-detection
   ```

3. Run the models:
   ```bash
   Run the corresponding ipynb files.
   ```
