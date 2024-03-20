## Black Board Teaching Materials
[Link to the Black Board Teaching Materials](https://github.com/Naif-Ganadily/GenerativeAI_FreeCodeCamp/blob/7d5169a494442b6d55988a316bf9254f70f2196f/Day1/Day%201.pdf)

## What you will learn?

- Generative AI ?
- Large Language Models (LLMs)
- OpenAI
- Langchain
- Vector Database
- Llama Index
- Open Source LLM Model
- End to End Projects


## Generative AI

- ChatGPT
- Google Bard **Update: Gemini and Gamma models**
- Meta Llama 2



## What is Generative AI?
Generative AI generate new data based on training sample. Generative model can generate Image, Text, Audio, Video etc. Data as output.

So generative AI is a very huge topic 
- Generative Image Model (GAN Model Image to Image)
- Generative Language Model
- - Text to Image
- - Text to Text
- - Image to Image




**For GAN Architecture (Popular between 2018 and 2019):**
Real Images ----> | Discriminator | ----> Real/Fake?
Random Input ----> | Generator | ----> Generated Images ---->

Explanation:
- "Real Images" are fed into the "Discriminator".
- "Random Input" is used by the "Generator" to create "Generated Images".
- The "Discriminator" then evaluates if the images from the "Generator" are "Real" or "Fake".

**(Expensive in Computation)**

## Description of Generative AI
**Generative AI is a subset of deep learning and Generative models are trained on huge amount of data.** While training the generative model we dont need to provide a label data, it is not possible when we have a huge amount of data, So, its just try to see the relationship between the distribution of the data. **In Generative AI we give unstructured data to the LLM model for training purpose.**

## Generative Model

Input Prompt ----> Output Prompt
Questions ----> Responses

## Where Geberative AI Exists
- Machine Learning is the subset of Artificial Intelligence
- Deep Learning is the subset of Machine Learning
- Generative AI is the subset of Deep Learning

## Reading List
- [Sequence to Sequence Learning with Neural Networks](https://arxiv.org/abs/1409.3215)
- [Neural Machine Translation with Attention](https://www.researchgate.net/publication/355917108_Neural_Machine_Translation_with_Attention)
- [Attention Is All You Need](https://arxiv.org/abs/1706.03762)

  
## Discriminative vs Generative Model
- **Discriminative Model:**
- - Passing the Inputs with Labels
- - Supervised Learning using Recurrent Neural Network (RNN)
- - Different Outputs

**Generative Models:**
- - Data Inputs
- - Unsupervised Learning ----> Supervised Fine Tunning ----> Reinforcement Learning
- - New Data Generation



## What is LLMs?
A Large Language Model is a trained deep learning model that understands and generate text in a human like fashion.

LLMs are good at Understanding, generating human language 

## Why we call it Large Language Model?
- Because of the size and complexity of the Neural Networks as well as the size of the dataset that it was trained on.
- Researchers started to make thse models large and trained on huge datasets
- That they started showing impressive results like understanding complex Natural Language and generating language more eloquently

## What makes LLM so Powerful?
- In case of LLM, one model can be used for a whole variaty of tasks like:
- - **Text Generation, Chatbot, Summarizer, Translation, Code Generation & so on....**
- LLM is a subset of Deep Learning & it has some properties merge with Generative AI 

## LLMs Model Architecture  
- Large Language models are based on Transformer a type of Neural Network Architecture invented by Google 

![1_R5WJ_nO0gKy2yk3HHGorhg](https://github.com/Naif-Ganadily/GenerativeAI_FreeCodeCamp/assets/103202628/062767b0-5387-4c27-822b-0d42d9de5909)

## Few Milestones in Large Language Model
- **BERT**: Bidirectional Encoder Representations from Transformers (BERT) was developed by Google
- **GPT**: GPT stands for "Generative Pre-Trained Transformer". The model was developed by OpenAO 
- **XLM**: Cross-lingual Language Model Pretraining by Guillaume Lample, Alexis Conneau
- **T5**: The Text-to-Text Transfer Transformer it was created by Google AI
- **Megatron**: Megatron is a large, powerful transformer developed by a research team at NVIDIA
- **M2M-100**: Multilingual Encoder-Decoder (seq-to-seq) model developed by a research team at Meta

## Transformer Tree
- Some use only Encoder like (BERT, RoBERTa)
- Some use only Decoder like (GPT, GPT2, GPT3)
- Some use both like (T5, BART)

## OpenAI Based LLM Models
- **GPT-4**: A set of models that improve on GPT-3.5 and can understand as well as generate natural language or code
- **GPT-3.5**: A set of models that improve on GPT-3 and can understand as well as generate natural language or code
- **GPT base**: A set of models without instruction following that can understand as well as generate natural language or code
- **DALL.E**: A model that can generate and edit images given a natural language prompt
- **Whisper**: A model that can convert audio into text
- **Embeddings**: A set of models that can convert text into a numerical form
- **Moderation**: A fine-tuned model that can detect whether text may be sensitive or unsafe
- **GPT-3 Legacy**: A set of models that can understand and generate natural language 

## Other Open Source Models
- BLOOM
- Llama 2
- PaLM
- Falcon 
- Claude
- MPT-30B
- Stablelm
and so on...

## What can LLM be used for?
- Text Classification 
- Text Generation 
- Text Summarization
- Conversation AI like chatbot, Question and Answering
- Speech recognition and Speech identification
- Spelling Corrector
and so on...

## Prompt Designing 
All the text that we feed into an LLM as input is called a prompt and this whole art is known as prompt design, which is about figuring out how to write and format prompt text to get LLMs to do what you want

## How ChatGPT was trained
Internally using which is gpt-3.5 or gpt-4
It has trained on a large amount of data which is available all over the internet.

1. Generative pre-training
2. Supervised fine-tuning 
3. Reinforcement learning



References:
- https://www.google.com/url?sa=i&url=https%3A%2F%2Fblog.gopenai.com%2Fhow-transformers-and-large-language-models-llms-work-3f20bb41c1ff&psig=AOvVaw37HbOvWzYVaX73J-NUeLjQ&ust=1709334254610000&source=images&cd=vfe&opi=89978449&ved=0CBUQjhxqFwoTCIjGnLrU0YQDFQAAAAAdAAAAABAE
- https://arxiv.org/abs/1706.03762
- https://arxiv.org/abs/1409.0473
- https://arxiv.org/abs/1409.3215
  
