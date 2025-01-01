# Medical-RAG-System
A locally deployed Retrieval-Augmented Generation (RAG) system for medical case analysis, using retrievers (Bio_ClinicalBERT, all-mpnet-base-v2) and generators (Medical-Llama3-8B, gemma-2-2b). Comprehensive evaluation with metrics like Precision@k, Recall@k, BLEU, and ROUGE ensures robust, privacy-focused performance in healthcare.

## Features

- **Privacy-Centric Deployment**: Local implementation ensures data privacy and complies with healthcare regulations.
- **Advanced AI Models**: Utilizes Bio_ClinicalBERT for retrieval and Medical-Llama3-8B for generation.
- **Robust Evaluation Metrics**: Assesses performance with Precision@k, Recall@k, F1-score, BLEU, and ROUGE scores.
- **Interactive Chat Interface**: Facilitates seamless interaction for comparing and analyzing medical case summaries.

## System Overview
![FlowChart](https://github.com/user-attachments/assets/2c5af9bf-d3c7-4a75-b9ad-ca6c4da40007)

The system works as follows:
1. Upload medical case documents (PDF format).
2. Text preprocessing and chunking for optimal data handling.
3. Embedding generation using domain-specific models.
4. Relevant text retrieval using similarity scores.
5. Response generation with contextual understanding.
6. Evaluation to ensure system accuracy and reliability.

## Technical Stack

- **Programming Language**: Python 3.10
- **Libraries**:
  - PyTorch, Hugging Face Transformers, SentenceTransformers
  - FAISS, spaCy, PyPDF2, NumPy
    
- **Models**:
  - Retriever: all-mpnet-base-v2, Bio_ClinicalBERT
  - Generator: gemma-2-2b, Medical-Llama3-8B

