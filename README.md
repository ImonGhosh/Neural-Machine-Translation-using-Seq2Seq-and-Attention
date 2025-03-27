# Neural-Machine-Translation-using-Seq2Seq-and-Attention

Process Overview
Dataset Preparation

Uses a small, preprocessed Hungarian-English dataset from Tatoeba.

Sentences are normalized for Unicode (e.g., accented characters are handled).

Punctuation is separated and preserved as distinct tokens.

Preprocessing

Normalization and tokenization of sentences.

Padding sequences and creating word-index mappings.

Model 1: Seq2Seq without Attention

Utilizes two LSTMs: one for the encoder and one for the decoder.

Trains the model to learn a direct mapping between source (Hungarian) and target (English) sentences.

Model 2: Seq2Seq with Attention

Adds an attention layer to help the decoder focus on relevant parts of the input sequence.

Improves translation accuracy and performance.

Training and Evaluation

Both models are trained and evaluated on validation/test sets.

Accuracy and qualitative performance (i.e., sample translations) are analyzed.
