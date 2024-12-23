# SnakModel：训练开放的丹麦大型语言模型所得的经验教训

发布时间：2024年12月17日

`LLM应用` `丹麦语言`

> SnakModel: Lessons Learned from Training an Open Danish Large Language Model

# 摘要

> 我们推出了 SnakModel，这是基于 Llama2-7B 的丹麦大型语言模型，我们对其在 136 亿个丹麦单词上持续预训练，还在 370 万条丹麦指令上进一步微调。由于针对较小语言群体创建 LLM 的最佳实践尚未确定，我们在整个训练流程中考察了早期建模和训练决策对下游性能的影响，涵盖（1）从各种来源创建严格筛选的丹麦文本语料库；（2）语言建模和指令微调的训练过程本身，包括对中间训练动态的分析以及不同超参数的消融实验；（3）在八项语言和文化特定任务上进行评估。在这些实验中，SnakModel 总体性能最佳，胜过多个当代基于 Llama2-7B 的模型。通过将 SnakModel、我们的大部分预训练语料库及相关代码以开放许可的形式提供，我们期望推动丹麦自然语言处理的进一步研究与发展，并为具有类似资源限制的语言确立训练准则。

> We present SnakModel, a Danish large language model (LLM) based on Llama2-7B, which we continuously pre-train on 13.6B Danish words, and further tune on 3.7M Danish instructions. As best practices for creating LLMs for smaller language communities have yet to be established, we examine the effects of early modeling and training decisions on downstream performance throughout the entire training pipeline, including (1) the creation of a strictly curated corpus of Danish text from diverse sources; (2) the language modeling and instruction-tuning training process itself, including the analysis of intermediate training dynamics, and ablations across different hyperparameters; (3) an evaluation on eight language and culturally-specific tasks. Across these experiments SnakModel achieves the highest overall performance, outperforming multiple contemporary Llama2-7B-based models. By making SnakModel, the majority of our pre-training corpus, and the associated code available under open licenses, we hope to foster further research and development in Danish Natural Language Processing, and establish training guidelines for languages with similar resource constraints.

[Arxiv](https://arxiv.org/abs/2412.12956)