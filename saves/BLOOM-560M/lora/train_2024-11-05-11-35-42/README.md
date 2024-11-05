---
library_name: peft
license: other
base_model: bigscience/bloom-560m
tags:
- llama-factory
- lora
- generated_from_trainer
model-index:
- name: train_2024-11-05-11-35-42
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# train_2024-11-05-11-35-42

This model is a fine-tuned version of [bigscience/bloom-560m](https://huggingface.co/bigscience/bloom-560m) on the identity and the alpaca_en_demo datasets.

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
- eval_batch_size: 8
- seed: 42
- distributed_type: multi-GPU
- num_devices: 2
- gradient_accumulation_steps: 8
- total_train_batch_size: 32
- total_eval_batch_size: 16
- optimizer: Use adamw_torch with betas=(0.9,0.999) and epsilon=1e-08 and optimizer_args=No additional optimizer arguments
- lr_scheduler_type: cosine
- num_epochs: 3.0

### Training results



### Framework versions

- PEFT 0.12.0
- Transformers 4.46.1
- Pytorch 2.4.1+cu121
- Datasets 3.1.0
- Tokenizers 0.20.2