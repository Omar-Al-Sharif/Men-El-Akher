---
tags:
- generated_from_trainer
model-index:
- name: AlQalam-finetuned-mmj-withXlsumValid
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# AlQalam-finetuned-mmj-withXlsumValid

This model is a fine-tuned version of [malmarjeh/t5-arabic-text-summarization](https://huggingface.co/malmarjeh/t5-arabic-text-summarization) on the None dataset.
It achieves the following results on the evaluation set:
- Loss: 3.9824

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 0.0005
- train_batch_size: 24
- eval_batch_size: 24
- seed: 42
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: linear
- num_epochs: 4

### Training results

| Training Loss | Epoch | Step  | Validation Loss |
|:-------------:|:-----:|:-----:|:---------------:|
| 1.4795        | 1.0   | 3171  | 4.1343          |
| 1.3288        | 2.0   | 6342  | 4.0455          |
| 1.219         | 3.0   | 9513  | 3.9557          |
| 1.1531        | 4.0   | 12684 | 3.9824          |


### Framework versions

- Transformers 4.30.2
- Pytorch 2.0.1+cu118
- Datasets 2.13.1
- Tokenizers 0.13.3
