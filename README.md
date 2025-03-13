# 🚀 Fine-Tuning DeepSeek-R1-Distill-Mistral-7B on Kaggle

This notebook demonstrates how to fine-tune and run inference with **DeepSeek-R1-Distill-Qwen-7B** and **Mistral-7B-Instruct** models using Hugging Face's `transformers` library. It focuses on optimizing **large language models (LLMs)** for reasoning, instruction-following, and conversational AI.

---

## 🏗️ Model Overview
- ✅ **DeepSeek-R1-Distill-Qwen-7B**: A distilled version of DeepSeek’s R1 model, optimized for **logical reasoning and long-context tasks** (supports **128k tokens**).
- ✅ **Mistral-7B-Instruct**: Fine-tuned for **instruction-following** with strong **conversation and coding capabilities**.

---

## 📥 Setup & Dependencies
- Installs required libraries:  
pip install torch transformers accelerate


- ✅ Configures **multi-GPU execution**.
- ✅ Enables **float16 precision** for memory efficiency.

---

## 🔄 Model Loading & Inference
- ✅ Loads **pretrained models** from Hugging Face.
- ✅ Uses **tokenizers** for text input processing.
- ✅ Performs **inference with various prompts**, including **math problem-solving and reasoning tasks**.

---

## 🎯 Fine-Tuning & Optimization
- ✅ Fine-tunes the model on **Kaggle GPUs**.
- ✅ Implements **gradient accumulation & mixed precision training**.
- ✅ Uses **cached model storage** to optimize disk usage on Kaggle.

---

## 📊 Evaluation & Output
- ✅ **Runs inference** on structured reasoning tasks.
- ✅ Displays **model-generated responses** for multiple prompts.

---

## 💾 Cleanup & Resource Management
- ✅ Clears GPU cache (`torch.cuda.empty_cache()`) to prevent memory overflow.
- ✅ Deletes large variables after execution to optimize memory.

---

## 🎯 Conclusion
This notebook provides a **hands-on guide** to running **DeepSeek-R1-Distill-Qwen-7B** and **Mistral-7B-Instruct** models on Kaggle. The models are **efficient, powerful, and suitable for advanced NLP tasks**, including **reasoning, chat-based AI, and long-context understanding**.

🚀 *Ideal for AI researchers and developers working on cutting-edge language model applications!*
