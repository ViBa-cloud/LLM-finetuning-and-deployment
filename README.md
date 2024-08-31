# LLM-finetuning

Natural Language to code language (SQL)

Datasets:

1. https://huggingface.co/datasets/b-mc2/sql-create-context ---- (76.8k records) - based on Spider and WikiSql.


Things to talk about:

1. Dataset Preparation and model selection

2. Pretrained LLMs Task formulation
  a. Translation modeling: T5 small (60M): https://huggingface.co/google-t5/t5-small
  b. Encoder-Decoder: BERT base (110M): https://huggingface.co/google-bert/bert-base-multilingual-cased
  c. Decoder only: GPT2 Medium (345M): https://huggingface.co/openai-community/gpt2-medium

3. Finetuning techniques comparison
  a. qlora
  b. lora
  c. Bitnet
  d. RLHF
  e. RAG

4. Performance and Evaluation metrics (High level)
  a. Latency
  b. Throughput
  c. Ablation study
  d. Single-hop vs multi-hop mechanism
  e. Scalability

5. Performance and Evaluation techniques
  a. Pruning and distillation
  b. Quantization
  c. RLHF

6. Evaluation (Low level)
   a. Hardware RAM usage
   b. Clock cycles
   c. Hardware counters profiling

7. Application and deployment
  a. Flask application
