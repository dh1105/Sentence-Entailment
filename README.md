# Sentence-Entailment
Benchmarking various Deep Learning models such as BERT, ALBERT, BiLSTMs on the task of sentence entailment using two datasets - MultiNLI and SNLI.

# Results
These correspond to the model benchmarks on 100k training samples of the MultiNLI dataset.

| Model        | Validation accuracy | Validation loss | Training accuracy | Training loss |
| -------------| ------------------- | -------------   | ----------------- | ------------- |
| BiLSTM       | 0.6104              | 0.8718          | 0.6014            | 0.8754        |
| BERT         | 0.7906              | 0.8490          | 0.9690            | 0.0916        |
| ALBERT       | 0.7110              | 0.7003          | 0.7405            | 0.6356        |
