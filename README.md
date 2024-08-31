
### Natural Language to code language (SQL)

## Datasets:

- https://huggingface.co/datasets/b-mc2/sql-create-context ---- (76.8k records) - based on Spider and WikiSql.


## Things to talk about:

- Dataset Preparation and model selection

-  Pretrained LLMs Task formulation
   -  a. Translation modeling: T5 small (60M): https://huggingface.co/google-t5/t5-small
   -  b. Encoder-Decoder: BERT base (110M): https://huggingface.co/google-bert/bert-base-multilingual-cased
   -  c. Decoder only: GPT2 Medium (345M): https://huggingface.co/openai-community/gpt2-medium

- Finetuning techniques comparison
  -  qlora
  - lora
  - Bitnet
  - RLHF
  - RAG

- Performance and Evaluation metrics (High level)
  - Latency
  - Throughput
  - Ablation study
  - Single-hop vs multi-hop mechanism
  - Scalability

- Performance and Evaluation techniques
  - Pruning and distillation
  - Quantization
  - RLHF

- Evaluation (Low level)
   - Hardware RAM usage
   - Clock cycles
   - Hardware counters profiling

- Application and deployment
  - Flask application
