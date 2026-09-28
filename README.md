# 🧠 Large Language Models — Vizuara

This repository documents my learning journey through the **Large Language Models (LLM) course by Vizuara on YouTube**.

The main focus of this repository is to understand **how Large Language Models work internally and how to build an LLM from scratch**, rather than only using existing LLM APIs.

The course closely follows the concepts and implementation approach from the book **Build a Large Language Model from Scratch**.

---

## 🎯 Objective

The goal of this repository is to build a strong understanding of:

* How Large Language Models work
* How Transformers power modern LLMs
* How an LLM is implemented from scratch
* How text is converted into tokens
* How token embeddings work
* How attention mechanisms work
* How Transformer blocks are constructed
* How GPT-style models are implemented
* How pretrained GPT-2 weights can be loaded into an LLM architecture

---

## 📚 Topics Covered

### 1. Introduction to LLMs

* What are Large Language Models?
* Why are they called "Large"?
* LLMs vs earlier NLP models
* Transformers as the foundation of modern LLMs
* LLM vs Generative AI vs Deep Learning vs Machine Learning
* Applications of LLMs

### 2. Building an LLM from Scratch

Understanding the major components required to build a GPT-style language model.

* Text data
* Tokenization
* Token IDs
* Input-target pairs
* Embeddings
* Positional embeddings
* Context length
* Batch processing

### 3. Attention Mechanism

Understanding how attention allows a model to determine relationships between tokens.

* Self-Attention
* Query
* Key
* Value
* Attention Scores
* Attention Weights
* Context Vectors
* Causal Attention

### 4. Multi-Head Attention

* Multiple attention heads
* Query, Key and Value projections
* Head dimensions
* Combining attention heads
* Multi-Head Attention implementation

### 5. Transformer Architecture

Understanding the architecture behind GPT-style LLMs.

* Transformer blocks
* Attention layers
* Feed-Forward Networks
* Layer Normalization
* Residual Connections
* Dropout
* Transformer block implementation

### 6. GPT-Style LLM

Building the major components of a GPT-style language model.

* GPT architecture
* Model configuration
* Transformer blocks
* Output layers
* Logits
* Next-token prediction
* Text generation

### 7. Training the LLM

Understanding the process used to train a language model.

* Training data
* Batches
* Loss calculation
* Cross-entropy loss
* Backpropagation
* Gradient calculation
* Optimizers
* Training loop
* Evaluation

### 8. Loading Pretrained GPT-2 Weights

Working with pretrained GPT-2 parameters and integrating them into the implemented architecture.

* GPT-2 pretrained weights
* GPT-2 parameter dictionary
* Downloading model weights
* Understanding pretrained parameters
* Mapping GPT-2 weights
* Loading weights into the custom LLM
* Testing the pretrained model

---

## 🛠️ Technologies Used

* **Python**
* **PyTorch**
* **NumPy**
* **Jupyter Notebook**
* **Git & GitHub**

---

## 📂 Repository Structure

```text
LLM-Vizuara/
│
├── 01_LLM_Basics/
│
├── 02_Tokenization/
│
├── 03_Embeddings/
│
├── 04_Attention/
│
├── 05_Causal_Attention/
│
├── 06_Multi_Head_Attention/
│
├── 07_Transformer/
│
├── 08_GPT/
│
├── 09_LLM_Training/
│
├── 10_Text_Generation/
│
├── 11_GPT2_Pretrained_Weights/
│
├── notes/
│
├── notebooks/
│
└── README.md
```

---

## 📈 Learning Progress

* [x] Introduction to LLMs
* [ ] Understanding Tokenization
* [ ] Token Embeddings
* [ ] Positional Embeddings
* [ ] Self-Attention
* [ ] Causal Attention
* [ ] Multi-Head Attention
* [ ] Transformer Architecture
* [ ] GPT Architecture
* [ ] Building an LLM from Scratch
* [ ] Training the LLM
* [ ] Text Generation
* [ ] Loading GPT-2 Pretrained Weights
* [ ] Testing the Pretrained Model

---

## 💻 Implementation Approach

Instead of treating an LLM as a black box, I am implementing and studying its individual components step by step.

```text
Raw Text
   ↓
Tokenization
   ↓
Token IDs
   ↓
Token Embeddings
   ↓
Positional Embeddings
   ↓
Self-Attention
   ↓
Multi-Head Attention
   ↓
Transformer Blocks
   ↓
GPT Model
   ↓
Next Token Prediction
   ↓
Generated Text
```

---

## 📖 Learning Resource

**Vizuara — Large Language Models Course**

The course provides detailed explanations and implementations focused on understanding LLMs and building them from scratch.

The lecture series uses **Build a Large Language Model from Scratch** by Sebastian Raschka as its key reference.

---

## 🚀 What I Aim to Understand

By completing this repository, I aim to understand not just **how to use an LLM**, but **what happens inside an LLM**:

> **Text → Tokens → Embeddings → Attention → Transformers → GPT → Prediction → Generated Text**

This repository will be continuously updated as I progress through the course.

---

## 👨‍💻 About Me

I am a **B.E. Artificial Intelligence & Machine Learning graduate** currently strengthening my understanding of **Large Language Models and Generative AI** through hands-on implementation.

### Current Focus

**Large Language Models • Transformers • Generative AI • Deep Learning**

---

### ⭐ Learning Philosophy

> **Understand → Implement → Experiment → Build**
