# HuffPost News Classification

#### Overview
A natural language processing project fine-tuning DistilBERT on HuffPost news headlines to classify articles into topic categories, demonstrating transformer-based text classification on a real-world multi-class problem.
 
#### Technical Details
- **Model**: DistilBERT (distilbert-base-uncased), fine-tuned for multi-class classification
- **Dataset**: HuffPost News Category Dataset (Kaggle)
- **Performance**: 74.4% accuracy, 0.661 macro-F1
- **Tools**: Python (HuggingFace Transformers, PyTorch, pandas, scikit-learn)
 
#### Key Findings
- Transformer-based embeddings significantly outperform classical bag-of-words approaches for headline classification
- Macro-F1 of 0.661 reflects meaningful performance across imbalanced category distribution
- Short headline text presents inherent ambiguity — performance ceiling is constrained by label overlap across categories
