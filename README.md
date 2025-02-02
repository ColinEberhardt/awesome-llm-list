# Large Language Models (LLMs)

There's an increasing number of Large Language Models, both closed and open source. For those looking at options, this repository provides an overview of those options, together with basic data about each option. 

## OPEN SOURCE MODELS
### 🐪 [Camel](https://huggingface.co/Writer/camel-5b-hf)  
Parameters: 5B, (20B coming)  
Origin: [Writer](https://writer.com)  
License: [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0)  
Release date: April 2023  
Paper:  
Commercial use possible: YES  
GitHub: https://github.com/basetenlabs/camel-5b-truss

### 🏛️ [Palmyra](https://huggingface.co/Writer/palmyra-base)  
Parameters: 5B, (20B coming)  
Origin: [Writer](https://writer.com)  
License: [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0)  
Release date: April 2023  
Paper:  
Commercial use possible: YES  
GitHub: 

### 🐎 [StableLM](https://stability.ai/blog/stability-ai-launches-the-first-of-its-stablelm-suite-of-language-models)  
Parameters: 3B, 7B, (15B, 65B coming)  
Origin: [Stability.ai](https://stability.ai)  
License: [CC BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/)  
Release date: April 2023  
Paper:  
Commercial use possible: YES  
GitHub: https://github.com/Stability-AI/StableLM  

### 🧱 [Databricks Dolly 2](https://www.databricks.com/blog/2023/04/12/dolly-first-open-commercially-viable-instruction-tuned-llm)  
Parameters: 12B  
Origin: [Databricks](https://www.databricks.com), an instruction tuned version of EleutherAI pythia  
License: [CC BY-SA-4.0](https://creativecommons.org/licenses/by-sa/4.0/)  
Release date: April 2023  
Paper:  
Commercial use possible: YES  
GitHub: https://github.com/databrickslabs/dolly  

### 🦙 [Vicuna](https://vicuna.lmsys.org/)  
Parameters: 13B  
Origin: [UC Berkeley, CMU, Stanford, and UC San Diego](https://vicuna.lmsys.org/)  
License: Requires access to LlaMA, trained on https://sharegpt.com conversations that potentially breaches OpenAI license  
Release date: April 2023  
Paper:  
Commercial use possible: NO  
GitHub: https://github.com/lm-sys/FastChat  

### 🧠 [Cerebras-GPT](https://www.cerebras.net/blog/cerebras-gpt-a-family-of-open-compute-efficient-large-language-models/)  
Parameters: 111M, 256M, 590M, 1.3B, 2.7B, 6.7B, and 13B  
Origin: [Cerebras](https://www.cerebras.net)  
License: [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0)  
Release date: March 2023  
Paper: [https://arxiv.org/abs/2304.03208](https://arxiv.org/abs/2304.03208)  
Commercial use possible: YES  

### 🦙 [Stanford Alpaca](https://crfm.stanford.edu/2023/03/13/alpaca.html)  
Parameters: 7B  
Origin: [Stanford](https://crfm.stanford.edu/2023/03/13/alpaca.html), based on Meta's LLaMA  
License: Requires access to LlaMA, trained on GPT conversations against OpenAI license  
Release date: March 2023  
Paper:   
Commercial use possible: NO  
GitHub: https://github.com/tatsu-lab/stanford_alpaca  

### 🔮 [EleutherAI pythia](https://github.com/EleutherAI/pythia)  
Parameters: 70M, 160M, 410M, 1B, 1.4B, 2.8B, 6.9B, 12BB  
Origin: [EleutherAI](https://www.eleuther.ai)  
License: [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0)  
Release date: February 2023  
Paper: https://arxiv.org/pdf/2304.01373.pdf  
Commercial use possible: YES  

### 🦙 [LLaMA](https://ai.facebook.com/blog/large-language-model-llama-meta-ai/)  
Parameters: 7B, 33B, 65B  
Origin: [Meta](https://ai.facebook.com/tools/)  
License: Model weights available for non-commercial use by application to Meta  
Release date: February 2023  
Paper: https://arxiv.org/abs/2302.13971  
Commercial use possible: NO  

### 🌸 [Bloom](https://bigscience.huggingface.co/blog/bloom)  
Parameters: 176B  
Origin: [BigScience](https://bigscience.huggingface.co)  
License: [BigScience Rail License](https://bigscience.huggingface.co/blog/the-bigscience-rail-license)  
Release date: July 2022  
Paper: https://arxiv.org/abs/2211.05100  
Commercial use possible: YES  

### 🌴 [Google PaLM](https://ai.googleblog.com/2022/04/pathways-language-model-palm-scaling-to.html)  
Parameters: 540B  
Origin: [Google](https://www.google.com)  
License: Unknown - only announcement of intent to open  
Release date: April 2022  
Paper: https://arxiv.org/abs/2204.02311  
Commercial use possible: Awaiting more information  

### 🤖 [GPT-NeoX-20B](https://huggingface.co/EleutherAI/gpt-neox-20b)  
Parameters: 20B  
Origin: [EleutherAI](https://www.eleuther.ai)  
License: [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0)  
Release date: January 2022  
Paper: https://aclanthology.org/2022.bigscience-1.9/  
Commercial use possible: YES  
GitHub: https://github.com/EleutherAI/gpt-neox

### 🤖 [GPT-J](https://huggingface.co/EleutherAI/gpt-j-6b)  
Parameters: 6B  
Origin: [EleutherAI](https://www.eleuther.ai)  
License: [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0)  
Release date: June 2021  
Paper:   
Commercial use possible: YES  

### 🍮 [Google FLAN-T5](https://ai.googleblog.com/2020/02/exploring-transfer-learning-with-t5.html)  
Parameters: 80M, 250M, 780M, 3B, 11B  
Origin: [Google](https://www.google.com)  
License: [Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0)  
Release date: October 2021  
Paper: https://arxiv.org/pdf/2210.11416.pdf  
Commercial use possible: YES  
GitHub: https://github.com/google-research/t5x

## COMMERCIAL MODELS
### [OpenAI](https://openai.com)
**GPT-4**  
Parameters: undeclared  
Availability: Wait-list https://openai.com/waitlist/gpt-4-api  
Fine-tuning: No fine-tuning yet available or announced.  
Paper: https://arxiv.org/abs/2303.08774  
Pricing: https://openai.com/pricing  
Endpoints: Chat API endpoint, which also serves as a completions endpoint.  
Privacy: Data from API calls not collected or used to train models https://openai.com/policies/api-data-usage-policies

**GPT-3.5**  
Parameters: undeclared (GPT-3 had 175B)  
Availability: GA  
Fine-tuning: Yes, fine-tuning available through APIs.  
Paper: https://arxiv.org/pdf/2005.14165.pdf  
Pricing: https://openai.com/pricing  
Endpoints: A variety of endpoints available, including: chat, embeddings, fine-tuning, moderation, completions.  
Privacy: Data from API calls not collected or used to train models.

**ChatGPT**  
Parameters: undeclared (uses GPT-3.5 model)  
Availability: GA  
Fine-tuning: N/A - consumer web-based solution.  
Paper:  
Pricing: https://openai.com/pricing  
Endpoints: N/A - consumer web-based solution.   
Privacy: Data submitted on the web-based ChatGPT service is collected and used to train models https://openai.com/policies/api-data-usage-policies

## [AI21Labs](https://www.ai21.com)
**Jurassic-2**  
Parameters: undeclared (jurassic-1 had 178B)  
Availability: GA  
Fine-tuning: Yes, fine-tuning available through APIs.  
Paper:   
Pricing: https://www.ai21.com/studio/pricing   
Endpoints: A variety of endpoints available, including: task-specific endpoints including paraphrase, gramtical errors, text improvements, summarisation, text segmentation, contextual answers.  
Privacy:  


## [Anthropic](https://www.anthropic.com)
**Claude**  
Parameters: undeclared  
Availability: Waitlist https://www.anthropic.com/product   
Fine-tuning: Not standard, large enterprise may contact via https://www.anthropic.com/earlyaccess to discuss.    
Paper:  https://arxiv.org/abs/2204.05862   
Pricing: https://cdn2.assets-servd.host/anthropic-website/production/images/apr-pricing-tokens.pdf    
Endpoints: Completions endpoint.  
Privacy: Data sent to/from is not used to train models unless feedback is given - https://vault.pactsafe.io/s/9f502c93-cb5c-4571-b205-1e479da61794/legal.html#terms  


## [Google](https:google.com)  
**Google Bard**  
Parameters: 770M  
Availability: Waitlist https://bard.google.com   
Fine-tuning: No   
Paper:  
Pricing:  
Endpoints: Consumer UI only, API via PaLM  
Privacy: 


**Google PaLM API**  
Parameters: Upto 540B  
Availability: Announced but not yet available – https://blog.google/technology/ai/ai-developers-google-cloud-workspace/   
Fine-tuning: unknown   
Paper: https://arxiv.org/abs/2204.02311  
Pricing: unknown  
Endpoints: unknown  
Privacy: unknown


## [Amazon](https://aws.amazon.com)
**Amazon Titan**  
Parameters: unknown  
Availability: Announced but not yet available – https://aws.amazon.com/bedrock/titan/ai-developers-google-cloud-workspace/   
Fine-tuning: unknown   
Paper:   
Pricing: unknown  
Endpoints: unknown  
Privacy: unknown

## [Cohere](https://cohere.ai)
**Cohere**  
Parameters: 52B  
Availability: GA   
Fine-tuning:   
Paper:  
Pricing: https://cohere.com/pricing  
Endpoints: A variety of endpoints including embedding, text completion, classification, summarisation, tokensisation, language detection.  
Privacy: Data submitted is used to train models - https://cohere.com/terms-of-use