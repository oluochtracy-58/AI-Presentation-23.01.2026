Objective:

__**The goal is to process comments intelligently to extract meaning, keywords, sentiment, and recommendations.___

Method: Using Transformers (for sentiment analysis) and KeyBERT (for keyword extraction)

Input sequence – Raw comments since transformers work with sequence models for sentiment analysis.
Since KeyBERT is also a transformer based model. It not only understands meaning but produces also clean relevant keywords.

Embedding layer – Convert text into numbers because systems dont think in words but numbers. 
Each word has a specific number.

Self-attention – Focus is on important words and context. 
Transformers remember things that happened far back and see the whole picture, making it faster to train.

Feed-forward layers – This is the reasoning layer.
Transformers deal with pattern recognition by analyzing patterns and relationships

Output – Intelligent insights or recommendations
