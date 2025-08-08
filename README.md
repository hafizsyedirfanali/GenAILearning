# GenAILearning
Mastering Gen AI: Hugging Face, LangChain, and RAG
This repository documents my learning journey into the exciting world of Generative AI, focusing on the practical implementation of key techniques like Retrieval-Augmented Generation (RAG) using powerful open-source tools: Hugging Face and LangChain.
Description
This project explores building and experimenting with Generative AI applications. The project delves into:
Hugging Face Transformers: Using its collection of pre-trained models for tasks like text generation and embeddings.
LangChain: A framework for orchestrating and building end-to-end LLM-powered applications.
Retrieval-Augmented Generation (RAG): A technique that combines retrieval-based and generative models to create more informed and accurate outputs, especially when dealing with specific knowledge bases or external data sources.
The goal is to understand the interplay between these components to build intelligent and context-aware Gen AI solutions, including:
Building knowledge bases from documents.
Implementing efficient document chunking and embedding techniques.
Constructing RAG pipelines for answering questions or generating text based on retrieved information.
Key Learnings & Exploration Areas
This project focuses on:
Mastering LangChain and Hugging Face frameworks for Generative AI applications.
Deep diving into RAG techniques for building accurate question-answering and content generation systems.
Exploring advanced concepts like vector databases, conversational memory, and tool-based AI agents.
Implementing various approaches for interacting with Hugging Face models, including local pipelines and the Hugging Face Hub Inference API.
Understanding the importance of efficient data handling, including splitting documents into manageable chunks and creating embeddings for effective retrieval.
Getting Started
Follow these steps to set up the project and begin experimenting:
Dependencies
Ensure the following libraries are installed in your Python environment:
transformers: For interacting with Hugging Face models and pipelines.
sentence-transformers: For generating sentence embeddings.
langchain: The core framework for building LLM-powered applications.
langgraph: (If exploring graph-based applications).
torch: (For GPU acceleration with Sentence Transformers).
faiss-cpu (or faiss-gpu): For efficient similarity search in vector stores.
numpy: For numerical operations.
huggingface-hub: To interact with the Hugging Face Hub.
bash
pip install transformers sentence-transformers langchain torch faiss-cpu numpy huggingface-hub
Use code with caution.

Installation
Clone the repository:
Use code with caution.

Set up Hugging Face API Token:
Create a free account on Hugging Face.
Navigate to "Settings" -> "Access Tokens" and generate a new token with "read" permissions.
Create a .env file in the root directory of your project and add your token:
HUGGINGFACEHUB_API_TOKEN="hf_YOUR_HUGGING_FACE_API_TOKEN"
Executing Programs
Each section or experiment will likely have specific scripts. Detailed instructions will be provided within those sections. Generally, you'll run Python scripts:
bash
# Example: Running a RAG pipeline script
python rag_pipeline.py
Use code with caution.

Usage
This repository will contain various examples demonstrating different aspects of Hugging Face, LangChain, and RAG. Each example will include:
Description: Explaining the purpose and functionality of the code.
Dependencies: Any specific libraries required for that particular example.
Code Snippets: Demonstrating the implementation.
Usage Instructions: How to run and interact with the example.
Contributing
Contributions are welcome! If you'd like to contribute, please:
Fork the repository.
Create a new branch for your feature or bug fix.
Implement your changes and ensure they are well-documented.
Submit a pull request.
Please note that for contributions using Generative AI tools, they should be clearly marked with an "Assisted-By:" or "Generated-By:" label in commit messages, depending on the extent of AI-generated content. All contributions must be compatible with open-source licensing principles, as highlighted by the OpenInfra Foundation.
License
This project is licensed under the MIT License - see the LICENSE file for details.
Contact Information
Feel free to reach out with questions or feedback through GitHub issues
