# Day 10 — Semantic Search and Vector Retrieval

## 1. Objective

The objective of this session was to understand how semantic search helps AI applications retrieve information based on meaning rather than exact keyword matches. The session focused on query embeddings, similarity measures, vector retrieval, and the process of finding relevant information from a collection of documents. These concepts are important for building intelligent search systems and AI applications that provide contextually relevant responses.

## 2. Topics Covered

### Understanding Semantic Search

Semantic search is a technique used to find information based on the meaning and intent of a query rather than relying only on the exact words used. Traditional keyword-based search primarily looks for matching terms, whereas semantic search uses techniques such as embeddings to identify relationships between the query and stored content.

For example, a user searching for "ways to prepare for a job interview" may receive relevant results containing phrases such as "interview preparation tips" or "getting ready for a technical interview," even if the exact words do not match.

Semantic search is useful in document search systems, educational assistants, customer-support chatbots, and other applications where users may express the same idea in different ways.

### Query Embeddings and Similarity

In an embedding-based search system, the user's query is converted into a numerical vector using an embedding model. The system compares this query vector with the vectors stored in the database to identify semantically related content.

Different similarity measures can be used to compare vectors. One commonly used measure is **cosine similarity**, which compares the direction of two vectors. The choice of similarity measure depends on the embedding model and the retrieval system.

The search process generally involves:
- Converting the user's query into an embedding.
- Comparing it with stored document embeddings.
- Ranking candidate results according to similarity or a retrieval score.
- Returning the most relevant results for further processing.

### Vector Retrieval and Ranking

Vector retrieval is the process of finding stored vectors that are most relevant to a query vector. A system may retrieve the top-k results, meaning the highest-ranked number of candidate matches, based on its configured search method.

Retrieval quality depends on factors such as the quality of the embeddings, the relevance of the stored documents, the search configuration, and the wording of the query. A high similarity score does not always guarantee that a result contains the correct answer, so retrieved information may still require evaluation.

Metadata filtering can also help narrow the search. For example, an educational assistant could restrict retrieval to documents about placements or interview preparation before ranking the results.

### Applications of Semantic Search

Semantic search can be used in many AI-powered systems. A chatbot can search its knowledge base for information related to a user's question, while a document assistant can find relevant sections within a collection of files.

It can also support recommendation systems, FAQs, technical documentation search, and knowledge management tools. In RAG systems, semantic retrieval helps select useful context that is passed to an LLM before it generates an answer.

## 3. Research and Practical Work

During this session, I researched the difference between traditional keyword-based search and semantic search. I explored examples in which two questions use different words but communicate a similar meaning, and considered how embeddings can help a retrieval system identify relevant documents.

As part of the practical exploration, I reviewed the workflow of converting a query into an embedding, comparing it with stored document vectors, and retrieving the most relevant results. I also considered how changing a query or including more specific information might affect the returned results.

I examined the role of similarity measures and top-k retrieval in selecting candidate documents. This helped me understand that retrieval is not simply about finding a matching document; it also involves ranking results and assessing whether the retrieved information is useful for the original question.

Finally, I explored how semantic search can be combined with a language model in a RAG application. Retrieving relevant context before generating a response can help an application provide more grounded answers, although the quality of the final response still depends on the retrieved information and the model's use of that context.

## 4. Tools and Technologies

- **Embedding models:** Used conceptually to represent queries and documents as vectors.
- **Vector databases:** Studied for storing vectors and supporting retrieval.
- **Cosine similarity:** Learned as one method for comparing vector representations.
- **Top-k retrieval:** Explored as a way to select the highest-ranked search results.
- **Semantic search:** Studied for retrieving information based on meaning.

## 5. Learning Outcomes

By the end of this session, I understood how semantic search uses embeddings to identify relevant information even when the query and stored documents use different wording. I learned the basic process of query embedding, vector comparison, result ranking, and retrieval.

I also gained an understanding of how similarity measures, top-k retrieval, and metadata filtering can influence search results. These concepts strengthened my understanding of information retrieval and prepared me for the next session on Retrieval-Augmented Generation (RAG).
