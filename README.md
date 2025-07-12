
# FineTuning_Large_Language_Models_Using_LoRA_and_PEFT_with_HuggingFace_Transformers

This project demonstrates how to fine-tune large language models (LLMs) using **LoRA (Low-Rank Adaptation)** and **PEFT (Parameter-Efficient Fine-Tuning)** techniques with the **Hugging Face Transformers** library. It provides a lightweight, cost-effective approach to adapt transformer models for downstream tasks without updating all model parameters.

---

## ✅ Key Highlights

- Applied **LoRA** for efficient parameter tuning of transformer-based models.
- Used **PEFT** to reduce memory usage and training time.
- Integrated with Hugging Face's `transformers`, `datasets`, and `accelerate` libraries.
- Notebook-based implementation that is easy to follow and modify.
- Easily adaptable to any NLP task such as classification, summarization, or QA.

---

## 🛠️ Installation

Install required packages:

```bash
pip install transformers peft datasets accelerate
````

Optional (for optimization on CUDA-based GPUs):

```bash
pip install bitsandbytes
```

---

## 🚀 How to Run

1. Open the notebook:

```bash
jupyter notebook Peft_Lora.ipynb
```

2. Run each cell in sequence:

   * Load a pretrained model.
   * Apply LoRA adapters via PEFT.
   * Load your dataset.
   * Train and evaluate the model.

3. Customize the model or dataset as needed:

   * Change the base model (e.g., `bert-base-uncased`).
   * Use your own dataset with `load_dataset()`.
