# What's new in SAP HANA Vector Search feature

**The Vector Engine in SAP HANA Cloud will:**

- Facilitate storage of vector embeddings by introducing:
  - A new data type named REAL_VECTOR
  - A vector constructor TO_REAL_VECTOR, to create vector from strings
- Facilitate similarity search queries and analysis by introducing:

  - Two new distance calculating similarity search functions, L2Distance() and cosine_similarity(), to enhance the platform's capability to compute vector similarity.

**These features in turn will facilitate:**

- Storage and querying of vector embeddings in SAP HANA Cloud through SQL
- In-memory similarity searches to support retrieval-augmented generation (RAG) patterns
- Power to combine business data with graph, spatial, document, and vector data all on a single platform
- Storage and retrieval of contextual information for GenAI and intelligent data applications as vector embeddings

In the next section we provide steps involved in using these new features.
