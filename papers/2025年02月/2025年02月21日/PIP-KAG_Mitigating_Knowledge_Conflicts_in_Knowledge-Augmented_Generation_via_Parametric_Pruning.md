# # PIP-KAG：缓解知识增强生成中的知识冲突
通过参数剪枝方法，PIP-KAG成功解决了知识增强生成中的知识冲突问题。

发布时间：2025年02月21日

`LLM应用

理由：这篇论文讨论了如何通过知识增强生成（KAG）来更新大型语言模型（LLMs）的内部记忆，并提出了一种新的方法（PIP-KAG）来解决知识冲突问题。该方法通过剪枝LLMs的内部知识并引入适配模块，帮助模型更好地利用外部信息。此外，还构建了新的基准测试来评估上下文忠实度。这些内容属于LLM的应用和优化，因此归类为LLM应用。` `基准测试`

> PIP-KAG: Mitigating Knowledge Conflicts in Knowledge-Augmented Generation via Parametric Pruning

# 摘要

> 知识增强生成（KAG）通过整合外部知识在更新大型语言模型（LLMs）的内部记忆方面展现出巨大潜力。然而，当模型的内部记忆与外部信息产生矛盾时，KAG不可避免地会遇到知识冲突问题。目前缓解这些冲突的方法主要集中在提升外部知识的利用效率上，但这些方法的效果有限，因为内部知识仍然会对LLMs的生成过程产生影响。本文中，我们提出了一种基于参数化剪枝的知识增强生成方法（PIP-KAG），通过剪枝LLMs的内部知识并引入一个即插即用的适配模块，帮助模型更好地利用外部信息。此外，我们基于LLMs的幻觉现象构建了CoConflictQA基准测试，以便更好地评估回答问题时的上下文忠实度。实验结果表明，PIP-KAG显著减少了知识冲突并提升了上下文忠实度。值得注意的是，PIP-KAG将LLMs的参数减少了13%，在KAG框架下提升了模型的参数效率。所有代码均可在https://github.com/OpenBMB/PIP-KAG获取。

> Knowledge-Augmented Generation (KAG) has shown great promise in updating the internal memory of Large Language Models (LLMs) by integrating external knowledge. However, KAG inevitably faces knowledge conflicts when the internal memory contradicts external information. Current approaches to mitigating these conflicts mainly focus on improving external knowledge utilization. However, these methods have shown only limited effectiveness in mitigating the knowledge conflict problem, as internal knowledge continues to influence the generation process of LLMs. In this paper, we propose a ParametrIc Pruning-based Knowledge-Augmented Generation (PIP-KAG) approach, which prunes internal knowledge of LLMs and incorporates a plug-and-play adaptation module to help LLMs better leverage external sources. Additionally, we construct the CoConflictQA benchmark based on the hallucination of LLMs to better evaluate contextual faithfulness during answering questions. Experimental results on CoConflictQA demonstrate that PIP-KAG significantly reduces knowledge conflicts and improves context fidelity. Notably, PIP-KAG reduces LLM's parameters by 13%, enhancing parameter efficiency in LLMs within the KAG framework. All codes are available at https://github.com/OpenBMB/PIP-KAG.

[Arxiv](https://arxiv.org/abs/2502.15543)