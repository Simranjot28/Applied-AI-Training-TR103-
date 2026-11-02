# Day 9 — Embeddings and Vector Databases

## 1. Objective

The objective of this session was to understand how AI systems represent text as numerical data and use these representations to identify meaningful relationships between pieces of information. The session introduced embeddings, vector databases, and their role in semantic search and Retrieval-Augmented Generation (RAG). These concepts are useful for developing AI applications that need to retrieve relevant information from documents or knowledge bases.

## 2. Topics Covered

### Understanding Embeddings

Embeddings are numerical representations of data, such as text, images, or other supported inputs. In text-based AI applications, an embedding model converts words, sentences, or documents into vectors containing numerical values.

These vectors represent patterns and relationships learned by the model. Text with similar meanings may have embeddings that are closer together in the vector space, even when the wording is different.

For example, the sentences "How can I prepare for an interview?" and "What should I do before a job interview?" use different words but express similar ideas. An embedding-based system can identify their semantic similarity more effectively than a simple keyword-matching approach.

Embeddings are useful for:
- Semantic search and information retrieval.
- Finding similar documents or sentences.
- Grouping related text.
- Supporting recommendation systems and RAG applications.

### Understanding Vector Databases

A vector database is designed to store and retrieve vector representations efficiently. In AI applications, embeddings generated from documents can be stored alongside relevant text, identifiers, or metadata.

When a user submits a query, the system can generate an embedding for that query and compare it with stored vectors. It then retrieves the items that are most similar according to a selected similarity measure or search method.

Common concepts associated with vector databases include vector storage, similarity search, metadata filtering, and efficient retrieval of relevant information.

A vector database is particularly useful when an application needs to search a large collection of documents based on meaning rather than relying only on exact word matches.

### Embeddings and Vector Databases Together

Embeddings and vector databases serve different but complementary purposes. An embedding model converts information into numerical vectors, while a vector database stores those vectors and supports efficient retrieval.

A typical workflow includes the following steps:

1. Collect relevant documents or text.
2. Divide large documents into manageable sections when necessary.
3. Generate embeddings for the text sections.
4. Store the embeddings and associated information in a vector database.
5. Convert a user's query into an embedding.
6. Search for similar vectors and retrieve relevant information.

This process provides a foundation for semantic search and is commonly used as part of a RAG pipeline.

## 3. Research and Practical Work

During this session, I researched how embedding models represent text numerically and how these representations help AI applications identify relationships between different pieces of information. I explored the difference between keyword-based search and semantic search, focusing on how meaning can be more important than exact wording.

As part of the practical exploration, I considered examples involving interview preparation and educational questions. For instance, a system searching for interview advice could retrieve a relevant document even when the user's question uses wording different from that of the stored document.

I also examined the general workflow of generating embeddings, storing them with associated text, and retrieving relevant results through similarity search. This helped me understand how vector databases can organize information for AI applications.

The session introduced the relationship between embeddings, vector retrieval, and RAG. It provided a conceptual foundation for understanding how an AI assistant can search a knowledge base before generating a response.

## 4. Tools and Technologies

- **Embedding models:** Studied the conversion of text into numerical vectors.
- **Vector databases:** Explored the storage and retrieval of embeddings.
- **Similarity search:** Learned how systems identify related information.
- **Semantic search:** Examined retrieval based on meaning rather than exact keywords.
- **RAG concepts:** Studied how retrieved information can support LLM responses.

## 5. Learning Outcomes

By the end of this session, I understood what embeddings are and how they represent information in a numerical form. I learned how vector databases store these representations and help retrieve related information through similarity search.

I also understood the difference between keyword matching and semantic search and how embeddings and vector databases can work together in an AI application. These concepts established a foundation for the next session on semantic search and information retrieval.
