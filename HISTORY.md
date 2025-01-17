## 2.4.1

* Add missing hf_tokenizer_name in CLIPTextCfg.

## 2.4.0

* Fix #211, missing RN50x64 config. Fix type of dropout param for ResNet models
* Bring back LayerNorm impl that casts to input for non bf16/fp16 
* zero_shot.py: set correct tokenizer based on args
* training/params.py: remove hf params and get them from model config

## 2.3.1

* Implement grad checkpointing for hf model.
* custom_text: True if hf_model_name is set
* Disable hf tokenizer parallelism 

## 2.3.0

* Generalizable Text Transformer with HuggingFace Models (@iejMac)

## 2.2.0

* Support for custom text tower
* Add checksum verification for pretrained model weights 

## 2.1.0

* lot including sota models, bfloat16 option, better loading, better metrics

## 1.2.0

* ViT-B/32 trained on Laion2B-en
* add missing openai RN50x64 model

## 1.1.1

* ViT-B/16+
* Add grad checkpointing support
* more robust data loader
