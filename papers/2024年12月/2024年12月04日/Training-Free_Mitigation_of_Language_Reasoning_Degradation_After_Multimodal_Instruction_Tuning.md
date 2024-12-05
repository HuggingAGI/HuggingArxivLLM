# 无需训练即可减轻多模态指令调整后的语言推理能力退化

发布时间：2024年12月04日

`LLM应用` `多模态` `语言推理`

> Training-Free Mitigation of Language Reasoning Degradation After Multimodal Instruction Tuning

# 摘要

> 多模态模型通常把强大的大型语言模型（LLM）与视觉编码器相结合，然后通过指令调优在多模态数据上加以训练。虽说这一过程让LLM适应了多模态的环境，可这种适应是否会损害其原本的语言推理能力，目前还不清楚。在本项工作中，我们探究了多模态指令调优对语言推理性能的影响。我们聚焦于LLaVA，这是一个领先的多模态框架，它将Vicuna或Mistral等LLM与CLIP视觉编码器进行了整合。我们在八项语言推理任务里对比了原始LLM和其多模态适配版本的性能。我们的实验得出了若干关键的见解。其一，多模态学习对Vicuna和Mistral的影响各异：我们发现Mistral在多数任务中的语言推理能力下降，而Vicuna则在多数任务中有所提升。其二，虽然多模态指令学习在数学推理任务（如GSM8K）上一直使性能降低，但在常识推理任务（如CommonsenseQA）上却提升了性能。最后，我们证实了一种无需训练的模型合并技术能够有效减轻在多模态适配的Mistral中所观察到的语言推理能力下降的情况，甚至能提升视觉任务的性能。

> Multimodal models typically combine a powerful large language model (LLM) with a vision encoder and are then trained on multimodal data via instruction tuning. While this process adapts LLMs to multimodal settings, it remains unclear whether this adaptation compromises their original language reasoning capabilities. In this work, we explore the effects of multimodal instruction tuning on language reasoning performance. We focus on LLaVA, a leading multimodal framework that integrates LLMs such as Vicuna or Mistral with the CLIP vision encoder. We compare the performance of the original LLMs with their multimodal-adapted counterparts across eight language reasoning tasks. Our experiments yield several key insights. First, the impact of multimodal learning varies between Vicuna and Mistral: we observe a degradation in language reasoning for Mistral but improvements for Vicuna across most tasks. Second, while multimodal instruction learning consistently degrades performance on mathematical reasoning tasks (e.g., GSM8K), it enhances performance on commonsense reasoning tasks (e.g., CommonsenseQA). Finally, we demonstrate that a training-free model merging technique can effectively mitigate the language reasoning degradation observed in multimodal-adapted Mistral and even improve performance on visual tasks.

[Arxiv](https://arxiv.org/abs/2412.03467)