# Objective
The objective of this lab is to understand how generative models can be applied to sequential data such as text, time-series, or language sequences. Students will design and implement simple generative models capable of learning patterns from sequences and generating new sequences. 

# Learning Outcomes
After completing this lab, students will be able to:
1.	Understand sequential data and its characteristics
2.	Learn how generative models work for sequence prediction
3.	Implement sequence-based generative models using neural networks
4.	Train models to generate new sequences from learned patterns
5.	Evaluate the quality of generated sequences

## What are Generative Models for Sequences?
Generative models for sequences are machine learning models that learn patterns from sequential data and generate new sequences that resemble the training data.
Sequential data appears in many domains such as:
•	Natural Language Processing (text and sentences)
•	Speech recognition
•	Time-series forecasting
•	Music generation
•	DNA sequence analysis
These models predict the next element in a sequence based on previous elements..

## Common Approaches
•	N-gram language models
•	Recurrent Neural Networks (RNN)
•	LSTM / GRU networks
•	Transformer-based models (advanced)

# Experiment:
## Component–I: Sequence Generation using RNN / LSTM
### Tasks
1.	Load and preprocess the sequential dataset
2.	Convert sequences into numerical representations
3.	Create input-output sequence pairs
4.	Design an RNN or LSTM based generative model
5.	Train the model on the sequence dataset
6.	Generate new sequences using a seed input.
### Dataset
Use the following sequence dataset: 
machine learning models learn patterns from data.
sequence models process data step by step.
recurrent neural networks are designed for sequential tasks.
rnn models maintain hidden states across time steps.

long short term memory networks solve long dependency problems.
lstm uses gates to control information flow.
gru models simplify the lstm architecture.
sequence prediction is useful in many applications.

language modeling predicts the next word in a sentence.
speech recognition processes audio sequences.
time series forecasting predicts future values.
music generation creates new melodies.

generative models learn probability distributions.
they generate new samples similar to training data.
sequence generation is widely used in artificial intelligence.
deep learning improves sequence modeling performance.

### Expected Output
•	Generated sequence samples

## Component–II: Transformer Based Sequence Generation
### Tasks
1.	Use the same dataset as Component – I
2.	Perform word-level or subword tokenization
3.	Implement positional encoding for sequence order
4.	Design a Transformer-based architecture
5.	Train the model on the sequence dataset
### Expected Output
Generated sequences using the Transformer model
