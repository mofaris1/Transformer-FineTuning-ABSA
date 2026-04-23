# Advanced NLP: Transformer Fine-Tuning for Aspect-Based Sentiment Analysis (ABSA)

## Overview
This project demonstrates the practical application of State-of-the-Art (SOTA) Natural Language Processing techniques. It focuses on fine-tuning pre-trained Transformer models using the Hugging Face ecosystem to perform complex text analysis tasks, bridging the gap between foundational language modeling and business-oriented information extraction.

## Key Technical Achievements
1. **Transformer Fine-Tuning:**
   - Leveraged the Hugging Face `transformers` library and `Trainer` API to fine-tune large-scale architectures.
   - Evaluated the evolution of embeddings from standard Masked Language Modeling (BERT) to advanced disentangled attention mechanisms (ModernBERT/DeBERTa).
2. **Aspect-Based Sentiment Analysis (ABSA):**
   - Moved beyond binary sentiment classification to implement ABSA, enabling the model to extract specific aspects (e.g., "service", "price") and determine the nuanced sentiment associated with each distinct entity.
   - Differentiated practical use-cases between standard Named Entity Recognition (NER) and context-aware ABSA.
3. **Evaluation Metrics:**
   - Monitored training optimization over multiple epochs.
   - Evaluated model performance using rigorous metrics including Accuracy, F1-Score, Precision, and Recall.

## Technologies Used
- **Frameworks:** Hugging Face (Transformers, Datasets), PyTorch.
- **Models:** BERT / ModernBERT architectures.
- **Concepts:** Transfer Learning, Fine-Tuning, ABSA, NER, Masked Language Modeling (MLM).
