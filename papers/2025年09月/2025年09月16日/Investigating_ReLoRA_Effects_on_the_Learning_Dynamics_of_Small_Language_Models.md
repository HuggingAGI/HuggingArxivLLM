# 探究ReLoRA：对小型语言模型学习动态的影响

发布时间：2025年09月16日

`LLM理论` `基础理论`

> Investigating ReLoRA: Effects on the Learning Dynamics of Small Language Models

# 摘要

> LoRA等参数高效方法彻底革新了LLMs的微调技术，但将其通过ReLoRA扩展至预训练的研究却相对匮乏——尤其是在小型语言模型（SLMs）领域，这类模型的计算成本和环境代价更低。本研究首次针对SLMs（1100万-6600万参数）中的ReLoRA展开系统性研究，全面评估了其性能表现与学习动态。通过消融实验，我们发现ReLoRA在损失值、Paloma困惑度及BLiMP指标上的表现普遍逊于标准训练，且模型规模越大，性能差距越明显。对模型学习动态的深入分析显示，ReLoRA会加剧小型模型固有的秩缺陷。这些结果表明，低秩更新策略可能难以直接迁移至SLM的预训练过程，这也凸显了在低计算资源场景下开展更多研究的必要性。

> Parameter-efficient methods such as LoRA have revolutionised the fine-tuning of LLMs. Still, their extension to pretraining via ReLoRA is less well understood, especially for small language models (SLMs), which offer lower computational and environmental costs. This work is the first systematic study of ReLoRA in SLMs (11M-66M parameters), evaluating both performance and learning dynamics. Through ablation experiments, we find that ReLoRA generally performs worse than standard training on loss, Paloma perplexity and BLiMP, with the gap widening for the larger models. Further analysis of the learning dynamics of the models indicates that ReLoRA reinforces the rank deficiencies found in smaller models. These results indicate that low-rank update strategies may not transfer easily to SLM pretraining, highlighting the need for more research in the low-compute regime.

[Arxiv](https://arxiv.org/abs/2509.12960)