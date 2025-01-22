# Fine-Tuning LLaMA-3.2 Instruct with QLoRA

## Description
This repository contains a notebook for fine-tuning the `meta-llama/Llama-3.2-3B-Instruct` (or other generative language models) model using Quantized LoRA (QLoRA) for sentiment classification on the Arabic HARD dataset. This method allows efficient adaptation of large language models for specific tasks using low-rank approximations, reducing memory requirements and computational overhead.

## References
[![Tutorial]](https://www.youtube.com/watch?v=9wp0Gd9-pfE)

### HARD Dataset
- **Title**: Hotel Arabic-Reviews Dataset Construction for Sentiment Analysis Applications  
  **Authors**: A. Elnagar, Y. S. Khalifa, & A. Einea  
  **Publication**: Procedia Computer Science, Volume 142, 2018, Pages 182-189  
  **DOI**: [10.1016/j.procs.2018.10.466](https://doi.org/10.1016/j.procs.2018.10.466)  
  **GitHub Repository**: [HARD Dataset GitHub](https://github.com/elnagara/HARD-Arabic-Dataset)  

### QLoRA
- **Title**: QLoRA: Efficient Finetuning of Quantized LLMs  
  **Authors**: T. Dettmers, A. Pagnoni, A. Holtzman, & L. Zettlemoyer  
  **Publication**: *arXiv preprint*, arXiv:2305.14314, 2023  
  **ArXiv Link**: [arxiv.org/abs/2305.14314](https://arxiv.org/abs/2305.14314)  
  **GitHub Repository**: [QLoRA GitHub](https://github.com/artidoro/qlora)
