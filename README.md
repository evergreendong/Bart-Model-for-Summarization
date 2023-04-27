# Bart-Model-for-Summarization
BART is sequence-to-sequence model trained with denoising as pretraining objective. According to the resource,  https://github.com/facebookresearch/fairseq/tree/main/examples/bart  
I have evaluated the pretrained model **bart.large.cnn** by reproducing the results below

CNN/Daily Mail 
| Model | R1    | R2    | RL    |
|-------|-------|-------|-------|
| BERTSUMEXTABS | 42.13 | 19.60 | 39.18 |
| bart.large | 44.16 | 21.28 | 40.90 |
