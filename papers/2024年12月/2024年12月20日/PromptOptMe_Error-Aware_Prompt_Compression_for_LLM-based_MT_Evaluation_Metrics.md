# PromptOptMe：针对基于 LLM 的机器翻译评估指标的错误感知提示压缩技术

发布时间：2024年12月20日

`LLM应用` `机器翻译`

> PromptOptMe: Error-Aware Prompt Compression for LLM-based MT Evaluation Metrics

# 摘要

> 在自然语言处理（NLP）中，评估机器生成的自然语言内容质量是一项颇具挑战的任务。近来，诸如 GPT-4 之类的大型语言模型（LLMs）已被用于此，但由于复杂评估提示所需的大量令牌使用，其计算成本高昂。本文中，我们提出一种提示优化方法，利用较小的微调语言模型压缩输入数据用于评估提示，从而在使用更大的 LLMs 进行下游评估时降低令牌使用量和计算成本。我们的方法包含两个阶段的微调过程：监督微调，接着是偏好优化，依据人类偏好来优化模型的输出。我们聚焦于机器翻译（MT）评估，并以 GEMBA-MQM 指标为起点。结果显示，令牌使用量减少了 2.37 倍，评估质量却毫无损失。此项工作让像 GEMBA-MQM 这样先进的基于 LLM 的指标更具性价比和效率，提升了其广泛应用的可行性。

> Evaluating the quality of machine-generated natural language content is a challenging task in Natural Language Processing (NLP). Recently, large language models (LLMs) like GPT-4 have been employed for this purpose, but they are computationally expensive due to the extensive token usage required by complex evaluation prompts. In this paper, we propose a prompt optimization approach that uses a smaller, fine-tuned language model to compress input data for evaluation prompt, thus reducing token usage and computational cost when using larger LLMs for downstream evaluation. Our method involves a two-stage fine-tuning process: supervised fine-tuning followed by preference optimization to refine the model's outputs based on human preferences. We focus on Machine Translation (MT) evaluation and utilize the GEMBA-MQM metric as a starting point. Our results show a $2.37\times$ reduction in token usage without any loss in evaluation quality. This work makes state-of-the-art LLM-based metrics like GEMBA-MQM more cost-effective and efficient, enhancing their accessibility for broader use.

[Arxiv](https://arxiv.org/abs/2412.16120)