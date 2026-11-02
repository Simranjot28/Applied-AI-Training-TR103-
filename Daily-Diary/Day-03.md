# Day 3 — Transformer Architecture, Model Training, and Inference

## 1. Objective

The objective of this session was to understand the basic architecture behind modern Large Language Models and learn how transformer-based models process input data to generate meaningful outputs. The session also focused on the difference between model training and inference and how these processes contribute to the development and use of AI systems.

## 2. Topics Covered

### Transformer Architecture

The Transformer is a deep learning architecture widely used in modern language models. Unlike traditional sequence-processing approaches that handle information step by step, transformers can process relationships between tokens using an attention mechanism. This helps the model identify which parts of the input are important for understanding the context.

We discussed how text is converted into tokens and represented numerically before being processed by the model. Positional information is also incorporated so the model can account for the order of tokens in a sequence.

An important component of the transformer architecture is **self-attention**, which enables the model to determine how different tokens relate to one another. For example, when processing a sentence, the model can use surrounding words to interpret the meaning of a particular word more accurately.

The major components explored included:

- **Tokenization:** Dividing text into smaller units that can be processed by the model.
- **Embeddings:** Representing tokens as numerical vectors.
- **Positional information:** Helping the model account for token order.
- **Self-attention:** Identifying relationships between tokens in the input.
- **Feed-forward layers:** Further processing the representations learned by the attention layers.

### Model Training

Model training is the process through which a model learns patterns from data by adjusting its parameters. During the training of a language model, the model is commonly optimized to predict the next token in a sequence. The difference between its predictions and the expected targets is measured using a loss function, and an optimization algorithm updates the model parameters to improve performance.

We also discussed the importance of training data quality, computational resources, and model parameters. These factors influence the model's ability to learn useful patterns and generalize to new inputs.

### Model Inference

Inference refers to using an already trained model to produce a prediction or response for a given input. When a user submits a prompt to an LLM, the model processes the available context and generates an output based on its learned parameters.

Training and inference serve different purposes. Training involves learning and updating model parameters, whereas inference uses the trained parameters to generate results. Inference performance can depend on factors such as model size, input length, available hardware, and response-generation settings.

## 3. Research and Practical Work

During this session, I researched how transformer-based models form the foundation of modern language-processing systems. I explored the relationship between tokenization, embeddings, attention mechanisms, and the generation of text responses.

As part of the practical exploration, I examined how different prompts are processed by an AI language model and how the model generates responses based on the supplied context. I also considered how changing the wording or adding relevant information to a prompt can influence the resulting output.

I compared the concepts of training and inference to understand their different roles in the AI development lifecycle. This helped me recognize why developers can use an existing trained model through an interface or API without training a new model from scratch.

The research also highlighted the importance of computational resources. Training large models generally requires substantial computing power and data, while inference focuses on generating useful outputs efficiently when the model is deployed.

## 4. Tools and Technologies

- **Transformer architecture:** Studied attention mechanisms and the processing of token sequences.
- **Large Language Models:** Explored the relationship between model architecture and text generation.
- **AI-powered conversational tools:** Examined input processing and generated responses.
- **Deep learning concepts:** Tokenization, embeddings, model parameters, loss functions, training, and inference.

## 5. Learning Outcomes

By the end of this session, I developed a foundational understanding of transformer architecture and its importance in modern language models. I learned how tokenization and embeddings represent text, how self-attention helps identify relationships between tokens, and how feed-forward layers process the resulting representations.

I also understood the difference between training and inference and how each contributes to the development and deployment of AI applications. These concepts provided a technical foundation for exploring prompt engineering, embeddings, retrieval-augmented generation, and other Applied AI techniques in subsequent sessions.
