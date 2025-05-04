# Databricks Certified Generative AI Engineer Associate – Section 1 Practice

## 📘 Section 1: Design Applications – Scenario-Based Practice Questions

---

### **Question 1: Prompt Design for Structured Output**

A Generative AI Engineer is developing a chatbot that must return responses in a specific JSON format to integrate seamlessly with downstream systems.

**What is the most effective prompt design to achieve this?**

- A. "Provide a detailed answer to the user's question."  
- B. "Respond concisely to the user's query."  
- C. "Return your answer in the following JSON format: { 'response': '<your answer>' }."  
- D. "Answer the question as you see fit."  

**✅ Correct Answer:** C

**🧠 Explanation:**  
To ensure the model's output adheres to a specific structure, it's crucial to include explicit formatting instructions within the prompt. Option C provides a clear template, guiding the model to produce a JSON-formatted response, which facilitates seamless integration with downstream systems.

---

### **Question 2: Selecting the Appropriate Model Task**

A business requires an AI solution that can generate summaries of lengthy legal documents, capturing essential clauses and obligations.

**Which model task should the engineer prioritize?**

- A. Text classification  
- B. Named entity recognition  
- C. Summarization  
- D. Sentiment analysis  

**✅ Correct Answer:** C

**🧠 Explanation:**  
Summarization is the process of distilling the most important information from a source text. For lengthy legal documents, summarization enables the extraction of key clauses and obligations, providing concise overviews that are easier to comprehend and utilize.

---

### **Question 3: Designing a Multi-Stage Reasoning Pipeline**

An engineer is tasked with building an AI system that answers customer queries by retrieving information from a knowledge base and then generating a natural language response.

**Which sequence of components best accomplishes this task?**

- A. Prompt → LLM  
- B. Retriever → Prompt → LLM  
- C. LLM → Retriever → Prompt  
- D. Prompt → Retriever → LLM  

**✅ Correct Answer:** B

**🧠 Explanation:**  
In a Retrieval-Augmented Generation (RAG) setup, the system first retrieves relevant information from a knowledge base (Retriever), then constructs a prompt incorporating this information, and finally passes it to the Language Model (LLM) to generate a coherent response. This sequence ensures that the AI's answers are both contextually relevant and well-informed.

---

### **Question 4: Translating Business Goals into AI Pipeline Inputs and Outputs**

A company wants to automate the process of converting customer service call transcripts into structured data that identifies the customer's issue and the resolution provided.

**What should be the defined inputs and outputs for the AI pipeline?**

- A. Input: Audio files; Output: Sentiment score  
- B. Input: Text transcripts; Output: Structured data with issue and resolution fields  
- C. Input: Customer profiles; Output: Call summaries  
- D. Input: Support tickets; Output: Response time metrics  

**✅ Correct Answer:** B

**🧠 Explanation:**  
The goal is to process text transcripts of customer service calls to extract specific information: the customer's issue and the resolution provided. Therefore, the AI pipeline should take text transcripts as input and output structured data capturing these two elements, facilitating analysis and record-keeping.

---

### **Question 5: Ordering Tools for Multi-Stage Reasoning**

An AI application needs to perform the following steps: extract data from a document, interpret the data, and then generate a summary.

**What is the correct order of tools or components to achieve this?**

- A. Summarizer → Interpreter → Extractor  
- B. Extractor → Interpreter → Summarizer  
- C. Interpreter → Summarizer → Extractor  
- D. Extractor → Summarizer → Interpreter  

**✅ Correct Answer:** B

**🧠 Explanation:**  
The logical sequence starts with extracting data from the document (Extractor), then interpreting the extracted data to understand its context and meaning (Interpreter), and finally summarizing the interpreted information (Summarizer). This order ensures a coherent flow from raw data to meaningful summary.

---

