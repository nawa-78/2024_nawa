---
license: mit
tags:
- generated_from_trainer
metrics:
- accuracy
model-index:
- name: output_nasinasi2
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# output_nasinasi2

This model is a fine-tuned version of [rinna/japanese-gpt2-small](https://huggingface.co/rinna/japanese-gpt2-small) on an unknown dataset.
It achieves the following results on the evaluation set:
- Loss: 3.1048
- Accuracy: 0.4073

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 5e-05
- train_batch_size: 2
- eval_batch_size: 2
- seed: 42
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: linear
- num_epochs: 3.0

### Training results

| Training Loss | Epoch | Step | Validation Loss | Accuracy |
|:-------------:|:-----:|:----:|:---------------:|:--------:|
| 3.3494        | 1.0   | 375  | 3.1455          | 0.4033   |
| 3.0658        | 2.0   | 750  | 3.1111          | 0.4067   |
| 2.9826        | 3.0   | 1125 | 3.1048          | 0.4073   |


### Framework versions

- Transformers 4.30.2
- Pytorch 1.12.1+cu113
- Datasets 2.4.0
- Tokenizers 0.13.3