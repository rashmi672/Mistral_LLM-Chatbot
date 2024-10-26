## LLM Chatbot Using Mistral 7B ##
Mistral LLM is a sophisticated AI language model created by Mistral AI. It's designed to understand and produce text that sounds like it was written by a human. The "LLM" in its name stands for "Large Language Model," which means it's a very large and powerful AI.

One specific version of this AI is called Mistral 7B. The "7B" part refers to the number of parameters it has, which determines its complexity and capabilities. Mistral 7B is a newer and more advanced model than its predecessor, Llama 2 13B on various parameter. 

Mistral 7B has been trained on a massive amount of text data, allowing it to perform various language tasks. These tasks include generating text, answering questions, translating languages, and more. The AI is designed to produce text that is both logical and relevant to the given context.

**Key Features:**

1. Mistral 7B Power: Leveraging the advanced capabilities of the Mistral 7B language model.
2. Customizable Prompts: Tailor the chatbot's responses to specific use cases and user interactions.
3. Efficient Inference: Optimized inference pipeline for real-time responses.
4. User-Friendly Interface: A simple and intuitive user interface for seamless interaction.

This repository provides a step-by-step guide on building a powerful and versatile LLM chatbot using the Mistral 7B language model. We'll see into the key components, from data preparation and model training to deployment and user interaction.


**Prepare Data:**
For fine-tuning the model we are using **tatsu-lab/alpac** dataset which can be found on [huggingface](https://huggingface.co/datasets/tatsu-lab/alpaca) website. After this we will clean and preprocess the data to ensure compatibility with the model and move ahead with the fine-tuning step.

**Model Training (Optional):**
All the training codes are written in colaboratory file. 

**Model Inference:**
we can use the provided scripts to load the pre-trained Mistral 7B model and perform inference. Experiment with different prompts and parameters to fine-tune the responses.

**THANK YOU!!**