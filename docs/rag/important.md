# Why is Retrieval-Augmented Generation important?

LLMs are a key artificial intelligence (AI) technology powering intelligent chatbots and other natural language processing (NLP) applications. The goal is to create bots that can answer user questions in various contexts by cross-referencing authoritative knowledge sources. Unfortunately, the nature of LLM technology introduces unpredictability in LLM responses. Additionally, LLM training data is static and introduces a cut-off date on the knowledge it has.

## What challenges does the retrieval augmented generation approach solve?

### Problem 1: LLM models do not know your data

LLMs use deep learning models and train on massive datasets to understand, summarize and generate novel content. Most LLMs are trained on a wide range of public data so one model can respond to many types of tasks or questions. Once trained, many LLMs do not have the ability to access data beyond their training data cutoff point. This makes LLMs static and may cause them to respond incorrectly, give out-of-date answers or hallucinate when asked questions about data they have not been trained on.

### Problem 2: AI applications must leverage custom data to be effective

For LLMs to give relevant and specific responses, organizations need the model to understand their domain and provide answers from their data vs. giving broad and generalized responses. For example, organizations build customer support bots with LLMs, and those solutions must give company-specific answers to customer questions. Others are building internal Q&A bots that should answer employees' questions on internal HR data. How do companies build such solutions without retraining those models?

### Solution: Retrieval augmentation is now an industry standard

An easy and popular way to use your own data is to provide it as part of the prompt with which you query the LLM model. This is called retrieval augmented generation (RAG), as you would retrieve the relevant data and use it as augmented context for the LLM. Instead of relying solely on knowledge derived from the training data, a RAG workflow pulls relevant information and connects static LLMs with real-time data retrieval.

With RAG architecture, organizations can deploy any LLM model and augment it to return relevant results for their organization by giving it a small amount of their data without the costs and time of fine-tuning or pretraining the model.

### key challenges of LLMs include:

- Presenting false information when it does not have the answer.
- Presenting out-of-date or generic information when the user expects a specific, current response.
- Creating a response from non-authoritative sources.
- Creating inaccurate responses due to terminology confusion, wherein different training sources use the same terminology to talk about different things.

You can think of the Large Language Model as an over-enthusiastic new employee who refuses to stay informed with current events but will always answer every question with absolute confidence. Unfortunately, such an attitude can negatively impact user trust and is not something you want your chatbots to emulate!

RAG is one approach to solving some of these challenges. It redirects the LLM to retrieve relevant information from authoritative, pre-determined knowledge sources. Organizations have greater control over the generated text output, and users gain insights into how the LLM generates the response.
