# Approaches for RAG with Azure AI Search

## Architecture daigram

![Azure RAG Architecture](https://learn.microsoft.com/en-us/azure/search/media/retrieval-augmented-generation-overview/architecture-diagram.png#lightbox)

## Microsoft has several built-in implementations for using Azure AI Search in a RAG solution.

### Azure AI Studio:

Use a vector index and retrieval augmentation. [AI Studio](https://learn.microsoft.com/en-us/azure/ai-studio/concepts/retrieval-augmented-generation)

### Azure OpenAI Studio:

Use a search index with or without vectors. [Azure OpenAI](https://learn.microsoft.com/en-us/azure/ai-services/openai/concepts/use-your-data?tabs=ai-search)

### Azure Machine Learning,

Use a search index as a vector store in a prompt flow. [Vector index in prompt flow](https://learn.microsoft.com/en-us/azure/machine-learning/how-to-create-vector-index?view=azureml-api-2)

Curated approaches make it simple to get started, but for more control over the architecture, you need a custom solution. These templates create end-to-end solutions in

### References:

Azure Reference [link](https://learn.microsoft.com/en-us/azure/search/retrieval-augmented-generation-overview)

[Azure GPT-RAG](https://github.com/Azure/GPT-RAG)
