<h1 align="center"> RAG - Retrieval-Augmented Generation</h1>

This project demonstrates the process of creating a vector database using Chroma for document retrieval and question-answering tasks, leveraging the power of Langchain and OpenAI embeddings. The primary goal is to convert Markdown documents into a searchable vector database and perform context-based retrieval using the Retrieval-Augmented Generation (RAG) approach.

![image](https://github.com/user-attachments/assets/364f02d8-9074-469a-9731-6a0bdfbb0472)


<h2>Features</h2>
<ul>
    <li>Markdown Document Processing: Load and process Markdown files into text chunks using Langchain's DirectoryLoader.</li>
    <li>Text Chunking: Split documents into manageable chunks for efficient vector embedding and retrieval.</li>
    <li>Vector Database Creation: Utilize Chroma to store and manage document embeddings, enabling fast similarity search.</li>
    <li>Retrieval-Augmented Generation (RAG): Perform context-based retrieval and question answering using OpenAI's embeddings and language models.</li>
</ul>

<h2>Usage</h2>
<ul>
    <li>To create the vector database from your Markdown documents, run: python create_database.py</li>
    <li>To perform a question-answering task using the RAG approach, execute: python query_data.py "Your question here"</li>
</ul>

<h2>Example</h2>
<ul>
    <li>Using RAG to ask questions about the book "Alice in Wonderland"</li>
</ul>


![image](https://github.com/user-attachments/assets/65657a1b-76ab-4bec-a60b-8bfe45ceb407)
