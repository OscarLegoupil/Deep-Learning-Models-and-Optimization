# Deep Learning Course Notebooks  
*A collection of notebooks implementing fundamental deep learning concepts from scratch.*

## 📌 Overview  
This repository contains **Jupyter notebooks** created as part of a deep learning course. Each notebook focuses on a specific topic, implementing key deep learning models **without relying on high-level libraries like TensorFlow or PyTorch**, to reinforce a deep understanding of the underlying mechanics.

New notebooks will be added over time, covering various aspects of deep learning, from foundational architectures to optimization techniques.

---

## 📁 Notebooks  

### **1️⃣ Bigram Model**  
📌 *[Bigram model.ipynb](Bigram model.ipynb)*  

✅ Implements a **bigram character-level language model**, predicting the next character based on the previous one.  
✅ Uses **PyTorch tensors** to compute a **co-occurrence matrix** for learning character transitions.  
✅ Visualizes **character relationships** and probability distributions using `matplotlib`.  

**Key Concepts Covered:**  
- N-gram language modeling  
- Probability-based next-character prediction  
- PyTorch tensor operations  

---

### **2️⃣ Micrograd: Building an Autograd Engine from Scratch**  
📌 *[Micrograd.ipynb](Micrograd.ipynb)*  

✅ Recreates a **simple autograd engine**, inspired by `micrograd` (by Karpathy), to understand how backpropagation works.  
✅ Builds a **computational graph**, implementing **automatic differentiation** to compute gradients.  
✅ Serves as the foundation for understanding how deep learning frameworks like TensorFlow and PyTorch handle gradients internally.  

**Key Concepts Covered:**  
- Computational graphs  
- Forward and backward passes  
- Automatic differentiation  

---

