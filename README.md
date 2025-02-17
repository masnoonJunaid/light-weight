Lightweight Fine-Tuning with PEFT and Hugging Face
Project Overview
Lightweight fine-tuning is a powerful technique for adapting foundation models efficiently. This project demonstrates parameter-efficient fine-tuning (PEFT) using the Hugging Face peft library. By leveraging LoRA (Low-Rank Adaptation), we fine-tune a BERT-based model for text classification on the IMDb dataset while minimizing computational requirements.

Key Steps in the Project
Load and Evaluate a Pre-trained Model

Load bert-base-uncased and evaluate its initial accuracy on the IMDb dataset.
Fine-tune Using PEFT (LoRA)

Apply LoRA for efficient fine-tuning with minimal additional parameters.
Train the model using Hugging Face's Trainer API.
Evaluate and Compare Performance

Measure the fine-tuned model’s accuracy and compare it with the pre-trained baseline.
Perform inference on sample text to observe improvements.
Technologies Used
Python (PyTorch-based training)
Hugging Face Transformers & Datasets
PEFT (Parameter-Efficient Fine-Tuning) Library
LoRA (Low-Rank Adaptation)
Installation & Setup
bash
Copy
Edit
pip install -U datasets peft transformers torch
Running the Project
Execute the fine-tuning script:

bash
Copy
Edit
python fine_tune_peft.py
Results
The fine-tuned model achieves improved accuracy compared to the pre-trained baseline.
Inference is performed using the saved fine-tuned model.
Contributors
### Masnoon Junaid
