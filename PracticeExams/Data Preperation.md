# Databricks Certified Generative AI Engineer Associate – Section 2 Practice

## Section 2: Prepare Data and Models – Scenario-Based Practice Questions

---

### Question 1: Cleaning Multilingual Data for RAG

A Generative AI Engineer is preparing a corpus of multilingual documents for a RAG system that serves only English-language queries. Some documents contain mixed languages.

**What is the most effective preprocessing step to ensure consistency in the responses?**

- A. Remove all non-English documents using language detection  
- B. Translate all documents into English before indexing  
- C. Remove stopwords from all documents regardless of language  
- D. Tokenize documents using a multilingual tokenizer  

**Correct Answer:** B

**Explanation:**  
To ensure consistency in responses and relevant retrieval, it's best to translate all documents into English. This aligns the indexed knowledge with the expected query language and prevents retrieval mismatches due to language differences.

---

### Question 2: Handling Personally Identifiable Information (PII)

A team is fine-tuning a foundation model using support chat transcripts. The data contains customer names, phone numbers, and account IDs.

**Which approach should the engineer use before training the model?**

- A. Remove all numerical data from the transcripts  
- B. Anonymize PII using regex or a data masking tool  
- C. Use data as-is to preserve conversational context  
- D. Train a separate model to identify PII post-deployment  

**Correct Answer:** B

**Explanation:**  
Before training, it's essential to anonymize PII to ensure compliance with data privacy regulations and ethical AI practices. Tools like regex or data masking libraries can be used to redact or replace sensitive fields without impacting the model's ability to learn from the conversation flow.

---

### Question 3: Dataset Size and Model Overfitting

An engineer is fine-tuning a relatively small foundation model (e.g., 350M parameters) on a dataset of only 1,000 examples.

**What risk does the engineer face, and how can it be mitigated?**

- A. Underfitting; increase the number of parameters  
- B. Overfitting; apply regularization or data augmentation  
- C. Data leakage; use encrypted storage  
- D. Slow training; reduce batch size  

**Correct Answer:** B

**Explanation:**  
Small datasets combined with powerful models can easily lead to overfitting, where the model memorizes training examples instead of generalizing. Regularization techniques like dropout or early stopping, and data augmentation methods like paraphrasing, can help mitigate this.

---

### Question 4: Embedding Text for Semantic Search

An engineer needs to convert a collection of knowledge base articles into a format suitable for vector-based semantic search in a RAG system.

**What preprocessing step is critical before generating embeddings?**

- A. Lemmatize and remove all punctuation  
- B. Chunk text into semantically coherent passages  
- C. Convert text to lowercase only  
- D. Encode text into one-hot vectors  

**Correct Answer:** B

**Explanation:**  
Chunking large documents into meaningful passages ensures that embeddings capture focused semantic content. This improves the relevance and granularity of the retrieval step in a RAG system, especially when combined with embedding models like `text-embedding-ada-002`.

---

### Question 5: Choosing the Right Model for Embedding

A Generative AI Engineer must embed a product catalog to power a similarity-based recommendation engine.

**Which model type is most appropriate for this task?**

- A. A summarization model  
- B. A causal language model  
- C. An embedding model  
- D. A text generation model  

**Correct Answer:** C

**Explanation:**  
Embedding models are designed to transform text into vector representations that capture semantic similarity. These embeddings can then be used for similarity search, recommendations, and clustering tasks. Text generation or summarization models are not optimized for embedding generation.

---
checkout more questions here https://www.udemy.com/course/databricks-certified-generative-ai-engineer-practice-tests/?referralCode=FFB6E54DAB48E4C96FBC
