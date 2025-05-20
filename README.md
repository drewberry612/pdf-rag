# 💡 LLaMA Model Deployment & RAG on Oracle Cloud Infrastructure (OCI)

This project involved deploying a **LLaMA 3.2 1B** model on **Oracle Cloud Infrastructure (OCI)** as part of a collaboration between the **University of Essex** and **Oracle**. The goal was to provide students with a cloud-based API for experimentation, and to build a **Retrieval-Augmented Generation (RAG)** system that allows users to query PDF documents and receive contextually relevant responses from the model.

## 🤖 Application

The RAG system enables document-based question answering using machine learning. Users can upload a PDF, ask questions about its content, and receive informed, context-aware answers in return.

## 🛠️ Key Features

- **LangChain Integration**: Managed the orchestration of model responses, vector store queries, and prompt formatting.
- **Custom Embeddings**: Developed a custom HuggingFace-compatible embedding class for LLaMA (due to limited out-of-the-box support for this architecture).
- **NLTK for Text Preprocessing**: Used NLTK to enhance text representation and improve response quality.
- **Document QA**: Refined the system’s ability to process complex, multi-turn queries grounded in PDF content.
- **Model Experimentation**: Later integrated and tested **DeepSeek-R1** to compare document QA performance and assess alternative model capabilities.

## ☁️ Infrastructure

- **Model Hosted On**: Oracle Cloud Infrastructure (OCI) Compute Instance  
- **API Access**: Secure HTTP endpoints exposed for student use and experimentation  
- **Data Pipeline**: Document ingestion → Chunking → Embedding → Retrieval → Prompt → Generation  

## 🎯 Outcome

The project demonstrated practical deployment of generative models in a cloud environment, and highlighted approaches for:

- Customising LLM pipelines for academic or enterprise use cases  
- Implementing RAG in low-resource environments (1B model)  
- Exploring the balance between performance and cost when scaling AI solutions
