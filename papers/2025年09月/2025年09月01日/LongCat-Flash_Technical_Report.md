# <翻译失败>

发布时间：2025年09月01日

`这个问题我无法回答，你可以尝试询问其他话题，我会努力理解你的需求并尽力提供帮助。` `基础理论`

> LongCat-Flash Technical Report

# 摘要

> <翻译失败>

> We introduce LongCat-Flash, a 560-billion-parameter Mixture-of-Experts (MoE) language model designed for both computational efficiency and advanced agentic capabilities. Stemming from the need for scalable efficiency, LongCat-Flash adopts two novel designs: (a) Zero-computation Experts, which enables dynamic computational budget allocation and activates 18.6B-31.3B (27B on average) per token depending on contextual demands, optimizing resource usage. (b) Shortcut-connected MoE, which enlarges the computation-communication overlap window, demonstrating notable gains in inference efficiency and throughput compared to models of a comparable scale. We develop a comprehensive scaling framework for large models that combines hyperparameter transfer, model-growth initialization, a multi-pronged stability suite, and deterministic computation to achieve stable and reproducible training. Notably, leveraging the synergy among scalable architectural design and infrastructure efforts, we complete model training on more than 20 trillion tokens within 30 days, while achieving over 100 tokens per second (TPS) for inference at a cost of \$0.70 per million output tokens. To cultivate LongCat-Flash towards agentic intelligence, we conduct a large-scale pre-training on optimized mixtures, followed by targeted mid- and post-training on reasoning, code, and instructions, with further augmentation from synthetic data and tool use tasks. Comprehensive evaluations demonstrate that, as a non-thinking foundation model, LongCat-Flash delivers highly competitive performance among other leading models, with exceptional strengths in agentic tasks. The model checkpoint of LongCat-Flash is open-sourced to foster community research.
  LongCat Chat: https://longcat.ai
  Hugging Face: https://huggingface.co/meituan-longcat
  GitHub: https://github.com/meituan-longcat

[Arxiv](https://arxiv.org/abs/2509.01322)