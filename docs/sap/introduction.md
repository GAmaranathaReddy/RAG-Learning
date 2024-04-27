# SAP Hana Cloud - Vector DB - RAG

The SAP HANA Cloud's Vector Engine addresses the challenges associated with solving GenAI scenarios. The Vector Engine is a new, multi-model engine that empowers users to store and query vector embeddings seamlessly, treating them like any other data types.

Here, we document the steps involved to in using the HANA's Vector Search Engine capability together with the IES GenAI Platform LLMs.

We have a set of PoCs that we have conducted for using our IES GenAI Platform LLMs for generating embedding and also how one could build a simple Retrieval Augmented Generation use case using these LLMs along with HANA DB.

Link to the VectorDB PoC Notebooks can be found here:

- [Generating and Storing embeddings inside HanaDB using AICore RestAPI](../sap/SAP-HANA-Cloud-VectorEngine-PoC/Generate-and-store-embeddings_with-HanaDB-AICore-RestAPI.ipynb)
- [Generating and Storing embeddings inside HanaDB using AICore PythonSDK](../sap/SAP-HANA-Cloud-VectorEngine-PoC/Generate-and-store-embeddings_with-HanaDB-AICore-PythonSDK.ipynb)
- [Retrieval Augmented Generation (RAG) use case with HanaDB using AICore RestAPI](../sap/SAP-HANA-Cloud-VectorEngine-PoC/Retrieval-Augmented-Generation_with-HanaDB-AICore-RestAPI.ipynb)
- [Retrieval Augmented Generation (RAG) use case with HanaDB using AICore PythonSDK](../sap/SAP-HANA-Cloud-VectorEngine-PoC/Retrieval-Augmented-Generation_with-HanaDB-AICore-PythonSDK.ipynb)

## Prerequisites

- [SAP AICore](https://help.sap.com/docs/sap-ai-core?locale=en-US)
- [SAP HANA Cloud](https://help.sap.com/docs/hana-cloud/sap-hana-cloud-getting-started-guide/introduction-to-sap-hana-cloud)
- [SAP GenAI HUB](https://help.sap.com/docs/sap-ai-core/sap-ai-core-service-guide/generative-ai-hub-in-sap-ai-core)
- [SAP LLM Commons](https://github.tools.sap/AI-Playground-Projects/llm-commons) (or)
- [SAP AICore LLM](https://pypi.org/project/sap-ai-core-llm/)
