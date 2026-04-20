# Generative Model with Attention

## Objective
Implement a text generation model using attention to improve contextual understanding.
Scenario
Build a chatbot that generates replies from user input. Use attention so the model focuses on important words in the sentence.

## Dataset
Cornell Movie Dialog Dataset (conversation pairs).
Example: Input: "Hello" → Output: "Hi, how are you?"
Steps
1. Preprocessing: clean text, tokenize, build vocabulary.
2. Model: Embedding → LSTM Encoder → Attention → Output layer.
3. Training: CrossEntropyLoss + Adam optimizer.
4. Evaluation: Check generated responses.

## Key Idea
Attention assigns weights to input words so the model focuses on relevant parts.
Expected Output
Input: "how are you"
Output: "i am fine"
Attention focuses more on "you".
