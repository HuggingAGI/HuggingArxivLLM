# 警惕差距：通过遵循式解码提升指令微调大语言模型的输出多样性

发布时间：2025年07月28日

`LLM理论` `创意写作`

> Mind the Gap: Conformative Decoding to Improve Output Diversity of Instruction-Tuned Large Language Models

# 摘要

> 指令微调会降低大型语言模型（LLMs）的输出多样性，这对创意任务尤为重要。本文聚焦于写作提示叙事生成任务中的“多样性差距”，发现这一差距在开源LLMs中普遍存在。研究显示，指令微调显著降低了模型的多样性。通过对OLMo和OLMo 2模型在各微调阶段的分析，我们发现DPO对多样性的影响最为显著。基于此，我们提出了一种新的解码策略——一致性解码，通过利用基础模型的多样性来指导指令模型，从而重新引入输出多样性。实验表明，一致性解码不仅提升了多样性，还保持或优化了输出质量。

> Instruction-tuning large language models (LLMs) reduces the diversity of their outputs, which has implications for many tasks, particularly for creative tasks. This paper investigates the ``diversity gap'' for a writing prompt narrative generation task. This gap emerges as measured by current diversity metrics for various open-weight and open-source LLMs. The results show significant decreases in diversity due to instruction-tuning. We explore the diversity loss at each fine-tuning stage for the OLMo and OLMo 2 models to further understand how output diversity is affected. The results indicate that DPO has the most substantial impact on diversity. Motivated by these findings, we present a new decoding strategy, conformative decoding, which guides an instruct model using its more diverse base model to reintroduce output diversity. We show that conformative decoding typically increases diversity and even maintains or improves quality.

[Arxiv](https://arxiv.org/abs/2507.20956)