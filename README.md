# Paraphrase Generator Model

This project targets two research qestions -

- How can changes in the learning rate (LR) affect the accuracy of the model?
  
- If two transformers are implemented in a row, would they perform better in terms of
accuracy/result?

# Dataset Used

- Paraphrase Adversaries From Word Scrambling (PAWS): This dataset contains 108,463 human-labeled and 656k noisily labeled pairs that
feature the importance of modeling structure, context, and word order information
for the problem of paraphrase generation.

# Models Used

- T5-base Transformer finetuned for Paraphrase generation
- PEGASUS Transformer: an Encoder-Decoder model with 2-pretrained objectives
  - GSG (Guided Summarization Generator) 
  - MLM (Masked Language Modeling)
 
# Evaluation Metric

- METEOR : Metric for Evaluation of Translation with Explicit Ordering
