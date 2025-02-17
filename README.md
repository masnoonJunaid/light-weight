# **Lightweight Fine-Tuning with PEFT and Hugging Face**

## **Project Overview**
Lightweight fine-tuning is a powerful technique for adapting foundation models efficiently. This project demonstrates **parameter-efficient fine-tuning (PEFT)** using the Hugging Face `peft` library. By leveraging **LoRA (Low-Rank Adaptation)**, we fine-tune a **BERT-based model** for text classification on the IMDb dataset while minimizing computational requirements.

## **Project Steps**
### **1. Load and Evaluate a Pre-trained Model**
- Load the `bert-base-uncased` model.
- Perform evaluation to establish a baseline accuracy.

### **2. Fine-tune Using PEFT (LoRA)**
- Apply **LoRA** for efficient fine-tuning with minimal additional parameters.
- Train the model using Hugging Face's `Trainer` API.

### **3. Evaluate and Compare Performance**
- Measure accuracy and compare the fine-tuned model with the pre-trained baseline.
- Perform inference on sample text to observe improvements.

## **Technologies Used**
- 🐍 **Python** (PyTorch-based training)  
- 🤗 **Hugging Face Transformers & Datasets**  
- 🔧 **PEFT (Parameter-Efficient Fine-Tuning) Library**  
- 🏗 **LoRA (Low-Rank Adaptation)**  

## **Installation & Setup**
To install the required dependencies, run:
```bash
pip install -U datasets peft transformers torch
