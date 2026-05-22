# sentiment-analysis-nip
 SENTIMENT ANALYSIS WITH NLP & TRANSFORMERS
   AI Academia Internship | Aditi Mrug | May 2026

   ABOUT
   End-to-end sentiment analysis on the IMDB Movie Reviews dataset.
   Compares classical ML, deep learning, and transformer-based approaches.

   MODELS BUILT
   1. Logistic Regression (TF-IDF baseline)
   2. Naive Bayes (TF-IDF baseline)
   3. Artificial Neural Network (PyTorch)
   4. DistilBERT Transformer (Hugging Face)

   DATASET
   IMDB Movie Reviews — 50,000 reviews (25k train, 25k test)
   Labels: Positive (1) and Negative (0)
   Source: Hugging Face datasets library

   KEY FINDINGS
Finding 1 (LinearSVC Bounds):** Our LinearSVC model achieved a peak accuracy score of approximately 88.04% on the validation test sample, outperforming the classical Logistic Regression baseline by a margin of 0.48%. This proves high-dimensional geometric configurations map clean textual splits efficiently.
Finding 2 (Review Length Patterns):** Exploratory Data Analysis reveals both positive and negative movie reviews share an identical median length clustering near 233 words. Review length alone is an uninformative indicator of emotional polarity.
Finding 3 (Predictive Keywords):** Feature coefficient evaluations show explicit adjectival tokens like "brilliant", "excellent", and "perfect" strongly anchor positive classifications, while "worst", "waste", and "boring" directly dictate negative labels.
Finding 4 (Neural Convergence):** The Artificial Neural Network (MLPClassifier) displayed excellent structural convergence across 5 epochs, steadily reducing cross-entropy loss from 0.4379 down to 0.1407.
Finding 5 (Production Viability):** Upgrading from a basic Naive Bayes framework to an optimized LinearSVC framework increases accuracy metrics by an absolute 4.06%, accurately preserving 1,015 reviews out of every 25,000 from misclassification queues.

   RESULTS SUMMARY
   Logistic Regression: 0.8756%
   Naive Bayes: 0.8398%
   ANN: 0.8459%
   DistilBERT: 0.8500%

   HOW TO RUN
   pip install pandas numpy matplotlib seaborn scikit-learn
   pip install transformers torch datasets
   Open Sentiment_Analysis_Final.ipynb in Jupyter and run all cells.

   AUTHOR
   Aditi Mrug — AI Academia AI/ML Internship 2025
