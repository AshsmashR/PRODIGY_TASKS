# PRODIGY_TASKS
PRODIGY_GA_01
This project focuses on text generation using "Pride and Prejudice" as a dataset, forming Task 1 of the "Looking Inward to an Atom of Gen AI" series. Two lightweight RNN models were developed using TensorFlow/Keras, leveraging pre-trained GloVe embeddings and the computational support of Google Colab’s free GPU T4. The first model includes an Embedding layer (non-trainable), a single LSTM layer with 256 units, and a Dense layer for vocab-size predictions. The second model introduces enhancements with trainable embeddings, deeper architecture including LSTM layers (256 and 128 units), Dropout (0.2), BatchNormalization, and kernel regularization to reduce overfitting. Despite these designs, the lack of explicit label generation resulted in low train and validation accuracies due to the unpredictable nature of context predictions. This project explores the fundamental principles of generative AI while balancing simplicity and computational efficiency.

PRODIGY_GA_03
This project  explores text generation using Markov Chains and bigrams, employing labeled data acquired from Kaggle. Markov Chains model the probability of transitioning from one state (word) to another, assuming that the next state depends only on the current state (first-order Markov property).
Simple Mathematical Explanation for Biologists:
If a sentence is modeled as a sequence of words, the probability of the next word depends only on the current word. 
