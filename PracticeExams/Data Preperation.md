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
Before training, it's essential to anonymize PII to ensure compliance with data privacy regulations and ethical AI practices. Tools like regex or data masking libraries can be used to redact or replace sensitive fields without impacting the model's
---

checkout more practice questions here

https://www.udemy.com/course/databricks-certified-generative-ai-engineer-practice-tests/?referralCode=FFB6E54DAB48E4C96FBC
