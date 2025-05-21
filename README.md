# Awesome-Federated-LoRA

## 📢 Updates
We released a survey paper "[Federated Low-Rank Adaptation for Foundation Models: A Survey](https://arxiv.org/abs/2505.13502)".

## 📒 Table of Contents

- [Awesome-Federated-LLM-Learning](#awesome-federated-lora)
  - [Part 1: Distributed Learning](#part-1-distributed-learning)
    - [1.1 Server Aggregation](#11-server-aggregation)
    - [1.2 LoRA Initialization](#12-lora-initialization)
  - [Part 2: Heterogenity](#part-2-heterogenity)
    - [2.1 Heterogeneous Rank](#21-heterogeneous-rank)
    - [2.2 Personalized LoRA](#22-personalized-lora)
    - [2.3 Clustering](#23-clustering)
  - [Part 3: Efficiency](#part-3-efficiency)
    - [3.1 Sparse Learning](#31-sparse-learning)
    - [3.2 Split Learning](#32-split-learning)
    - [3.3 Compression](#33-compression)


## Part 1: Distributed Learning
### 1.1 Server Aggregation
* Improving loRA in privacy-preserving federated learning. [[Paper]](https://arxiv.org/abs/2403.12313) 
* Towards Efficient Communication and Secure Federated Recommendation System via Low-rank Training. [[Paper]](https://dl.acm.org/doi/abs/10.1145/3589334.3645702)
* Robust Federated Finetuning of Foundation Models via Alternating Minimization of LoRA. [[Paper]](https://www.arxiv.org/abs/2409.02346)
* Towards Robust and Efficient Federated Low-Rank Adaptation with Heterogeneous Clients. [[Paper]](https://arxiv.org/abs/2410.22815)
* Federated Fine-tuning of Large Language Models under Heterogeneous Tasks and Client Resources. [[Paper]](https://arxiv.org/abs/2402.11505)
* Automated Federated Pipeline for Parameter-Efficient Fine-Tuning of Large Language Models. [[Paper]](https://arxiv.org/abs/2404.06448)
* FLoRA: Federated Fine-Tuning Large Language Models with Heterogeneous Low-Rank Adaptations. [[Paper]](https://arxiv.org/abs/2409.05976)
* LoRA-FAIR: Federated LoRA Fine-Tuning with Aggregation and Initialization Refinement. [[Paper]](https://arxiv.org/abs/2411.14961)
* FedEx-LoRA: Exact Aggregation for Federated and Efficient Fine-Tuning of Foundation Models. [[Paper]](https://arxiv.org/abs/2410.09432)
* FedInc: One-Shot Federated Tuning for Collaborative Incident Recognition. [[Paper]](https://link.springer.com/chapter/10.1007/978-3-031-72347-6_12)

### 1.2 LoRA Initialization
* SLoRA: Federated Parameter Efficient Fine-Tuning of Language Models. [[Paper]](https://arxiv.org/abs/2308.06522)
* FeDeRA:Efficient Fine-tuning of Language Models in Federated Learning Leveraging Weight Decomposition. [[Paper]](https://arxiv.org/abs/2404.18848)
* LoRA-FAIR: Federated LoRA Fine-Tuning with Aggregation and Initialization Refinement. [[Paper]](https://arxiv.org/abs/2411.14961)
* Communication-Efficient Federated Low-Rank Update Algorithm and its Connection to Implicit Regularization. [[Paper]](https://arxiv.org/abs/2409.12371)

## Part 2: Heterogenity
### 2.1 Heterogeneous Rank
* Heterogeneous LoRA for Federated Fine-tuning of On-Device Foundation Models. [[Paper]](https://arxiv.org/abs/2401.06432)
* RBLA: Rank-Based-LoRA-Aggregation for Fine-tuning Heterogeneous Models in FLaaS. [[Paper]](https://arxiv.org/abs/2408.08699)
* Towards Federated Low-Rank Adaptation of Language Models with Rank Heterogeneity. [[Paper]](https://arxiv.org/abs/2406.17477)

### 2.2 Personalized LoRA
* Dual-Personalizing Adapter for Federated Foundation Models. [[Paper]](https://arxiv.org/abs/2403.19211)
* FDLoRA: Personalized Federated Learning of Large Language Model via Dual LoRA Tuning. [[Paper]](https://arxiv.org/abs/2406.07925)
* Selective Aggregation for Low-Rank Adaptation in Federated Learning. [[Paper]](https://arxiv.org/abs/2410.01463)
* Personalized Federated Instruction Tuning via Neural Architecture Search. [[Paper]](https://arxiv.org/abs/2402.16919)
* Personalized Federated Fine-Tuning for LLMs via Data-Driven Heterogeneous Model Architectures. [[Paper]](https://arxiv.org/abs/2411.19128)
* FedMoE: Personalized Federated Learning via Heterogeneous Mixture of Experts. [[Paper]](https://arxiv.org/abs/2408.11304)
* Hyperflora: Federated learning with instantaneous personalization. [[Paper]](https://epubs.siam.org/doi/10.1137/1.9781611978032.94)

### 2.3 Clustering
* FL-TAC: Enhanced Fine-Tuning in Federated Learning via Low-Rank, Task-Specific Adapter Clustering. [[Paper]](https://arxiv.org/abs/2404.15384)
* FedLFC: Towards Efficient Federated Multilingual Modeling with LoRA-based Language Family Clustering. [[Paper]](https://aclanthology.org/2024.findings-naacl.98/)
* FedHLT: Efficient Federated Low-Rank Adaption with Hierarchical Language Tree for Multilingual Modeling. [[Paper]](https://dl.acm.org/doi/10.1145/3589335.3651933)

## Part 3: Efficiency
### 3.1 Sparse Learning
* Federated LoRA with Sparse Communication. [[Paper]](https://arxiv.org/abs/2406.05233)
* Federated LLMs Fine-tuned with Adaptive Importance-Aware LoRA. [[Paper]](https://arxiv.org/html/2411.06581v1)
* Fisher Information-based Efficient Curriculum Federated Learning with Large Language Models. [[Paper]](https://arxiv.org/abs/2410.00131)
* Fed-piLot: Optimizing LoRA Assignment for Efficient Federated Foundation Model Fine-Tuning. [[Paper]](https://arxiv.org/abs/2410.10200)
* FedFMSL: Federated Learning of Foundation Models With Sparsely Activated LoRA. [[Paper]](https://ieeexplore.ieee.org/document/10666083)
* FedRA: A Random Allocation Strategy for Federated Tuning to Unleash the Power of Heterogeneous Clients. [[Paper]](https://arxiv.org/abs/2311.11227)

### 3.2 Split Learning
* Federated Fine-Tuning for Pre-Trained Foundation Models Over Wireless Networks. [[Paper]](https://arxiv.org/abs/2407.02924)
* FedsLLM: Federated Split Learning for Large Language Models over Communication Networks. [[Paper]](https://arxiv.org/abs/2407.09250)
* SplitLoRA: A Split Parameter-Efficient Fine-Tuning Framework for Large Language Models. [[Paper]](https://arxiv.org/abs/2407.00952)

### 3.3 Compression
* CG-FedLLM: How to Compress Gradients in Federated Fune-tuning for Large Language Models. [[Paper]](https://arxiv.org/abs/2405.13746)
* FedBiOT: LLM Local Fine-tuning in Federated Learning without Full Model. [[Paper]](https://arxiv.org/abs/2406.17706)


