# Website Chatter using Advanced RAG

## 1. About the Dataset
This project involves creating a system to enhance interactions between humans and websites using advanced Retrieval-Augmented Generation (RAG) and LLMOps (Large Language Model Operations). The dataset consists of web data used to train and evaluate the interaction capabilities of the system.

## 2. Objective
The primary objectives of this project are to:
- Develop a system that improves human-website interactions by leveraging advanced RAG and LLMOps techniques.
- Utilize state-of-the-art tools and frameworks to enhance the quality and efficiency of web-based communication.

## 3. Approach
The project employs the following approach:
- **Data Ingestion & Processing:**
  - Implemented data ingestion using WebLoader and Beautiful Soup for scraping and parsing web content.
  - Used a recursive character splitter for effective chunking of text data.
- **Optimized Ranking & Retrieval:**
  - Integrated OpenAI Embeddings for semantic understanding.
  - Utilized Pinecone Vector DB for vector storage and retrieval.
  - Applied Hybrid Search and Cohere re-rankers to improve the ranking of search results.
- **Model & Framework Integration:**
  - Leveraged the Llama 3 Large Language Model (LLM) for fast inference with Langchain and Langsmith frameworks.
  - Ensured security and compliance with NVIDIA Nemo Guardrails.
- **Evaluation:**
  - Performed RAG evaluation using the RAGAS framework, achieving 84% faithfulness and 0.78 relevance for 100 sample interactions.

## 4. Results & Key Features
- **Performance:** Achieved an 84% faithfulness and a 0.78 relevance score in RAG evaluation, indicating high accuracy and reliability in interactions.
- **System Integration:** Successfully integrated advanced tools such as OpenAI Embeddings, Pinecone Vector DB, and Cohere re-rankers for optimized performance.
- **Security:** Implemented NVIDIA Nemo Guardrails to ensure system security and adherence to best practices.

## 5. License
This project is licensed under the MIT License.

## 6. Contact
For any questions or feedback regarding this project, please contact:
- **Vivek Radadiya**
