# fine-tuning-IndoBERT-for-masked-language-modeling
Domain adaptation on mental health dataset[[1]](#ref1)
## Result
Aku merasa sangat [MASK] --> Translation: I feel very [MASK]
| Rank | Prediction | Score  | Complete Sentence               |
|------|------------|--------|----------------------------------|
| 1    | sedih      | 0.119  | aku merasa sangat sedih.        |
| 2    | tertekan   | 0.114  | aku merasa sangat tertekan.     |
| 3    | sendirian  | 0.058  | aku merasa sangat sendirian.    |
| 4    | sakit      | 0.055  | aku merasa sangat sakit.        |
| 5    | gugup      | 0.046  | aku merasa sangat gugup.        |


Comparison with IndoBERT
| Rank | Original Prediction | Original Score | Fine-tuned Prediction | Fine-tuned Score |
|------|----------------------|----------------|------------------------|------------------|
| 1    | #vivian              | 0              | sedih                  | 0.119            |
| 2    | #hans                | 0              | tertekan               | 0.114            |
| 3    | gif                  | 0              | sendirian              | 0.058            |
| 4    | #harit               | 0              | sakit                  | 0.055            |
| 5    | #herto               | 0              | gugup                  | 0.046            |
## References
<a id="ref1"/>

[1] [Indonesian-mental-health-conversation-PSYCHIKA](https://www.kaggle.com/datasets/xmaulana/psychikadataset-7b)
