## GenAI Demo chatbot with Mistral 7B & Llama Index  
![](https://i.postimg.cc/j2r7R46V/gen-ai.png)



### Table of Content
  * [Benefits of Using Open-Source LLMs](#benefits-of-using-open-source-llms)
  * [Mistral 7B LLM](#mistral-7b-llm)
  * [LlamaIndex](llamaindex)
  * [Technical Stack](#technical-stack)
  * [Installation](#installation)



### Benefits of Using Open-Source LLMs 
Enhanced Data Security and Privacy:
Utilizing open-source LLMs mitigates concerns about data leaks and unauthorized access inherent in proprietary models. Companies adopting open-source LLMs retain control over sensitive data, ensuring greater accountability and privacy protection.

Cost Savings and Reduced Vendor Dependency:
Unlike proprietary LLMs, open-source alternatives generally incur no licensing fees, offering cost savings, particularly beneficial for small to medium-sized enterprises. However, operational costs for using cloud services or powerful infrastructure still apply.

Code Transparency and Language Model Customization:
Open-source LLMs provide visibility into their source code, architecture, and training mechanisms, facilitating scrutiny and customization. Companies can tailor these models to specific use cases, leveraging the openness of the source code.

Active Community Support and Fostering Innovation:
The open-source approach democratizes access to LLMs and generative AI technologies, encouraging global developer participation. Transparency enables scrutiny, reducing biases, improving accuracy, and fostering innovation. Lowering entry barriers promotes a collaborative community that enhances overall model performance.


### Mistral 7B LLM
Mistral 7B v0.1, a 7-billion-parameter language model engineered for superior performance and efficiency. Mistral 7B outperforms Llama 2 13B across all evaluated benchmarks, and Llama 1 34B in reasoning, mathematics, and code generation. Our model leverages grouped-query attention (GQA) for faster inference, coupled with sliding window attention (SWA) to effectively handle sequences of arbitrary length with a reduced inference cost. We also provide a model fine-tuned to follow instructions, Mistral 7B -- Instruct, that surpasses the Llama 2 13B -- Chat model both on human and automated benchmarks. Our models are released under the Apache 2.0 license.

### LlamaIndex
LlamaIndex (GPT Index) is a data framework for your LLM application.
Context
LLMs are a phenomenal piece of technology for knowledge generation and reasoning. They are pre-trained on large amounts of publicly available data.
How do we best augment LLMs with our own private data?
We need a comprehensive toolkit to help perform this data augmentation for LLMs.

Proposed Solution
That's where LlamaIndex comes in. LlamaIndex is a "data framework" to help you build LLM apps. It provides the following tools:

Offers data connectors to ingest your existing data sources and data formats (APIs, PDFs, docs, SQL, etc.)
Provides ways to structure your data (indices, graphs) so that this data can be easily used with LLMs.
Provides an advanced retrieval/query interface over your data: Feed in any LLM input prompt, get back retrieved context and knowledge-augmented output.
Allows easy integrations with your outer application framework (e.g. with LangChain, Flask, Docker, ChatGPT, anything else).


### Technical Stack 

- LlamaIndex
- Mistral 7B LLM
- HuggingFace Embeddings(model_name="thenlper/gte-large")


### Installation & Run
- Run this notebook with GPU availability(e.g. Google Cloud)
- Add your data to the folder & mention path in the code (currently the path is "/content/Data/")
  


![](https://res.cloudinary.com/cognitives-s3/image/upload/c_limit,dpr_auto,f_auto,fl_lossy,h_1900,q_auto,w_1900/v1/cog-live/n/1271/2023/Jan/30/XJjQaSivFeb8luqCBLAO.jpg)
