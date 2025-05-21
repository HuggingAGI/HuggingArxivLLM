# 辩论助力更优推理：无监督多模态方法探索

发布时间：2025年05月20日

`LLM应用` `视觉问答` `多模态`

> Debating for Better Reasoning: An Unsupervised Multimodal Approach

# 摘要

> 随着大型语言模型 (LLMs) 在多领域和多模态场景中展现出卓越能力，如何实现可扩展的监督机制成为一大挑战，尤其当模型能力超越人类评估者时。为此，我们引入辩论机制作为解决方案。本研究将辩论范式扩展至多模态环境，探索较弱模型监督并提升较强模型性能的可能性。以视觉问答 (VQA) 任务为例，两位“有视觉能力”的专家视觉-语言模型展开答案辩论，而一位“无视觉能力”（仅文本处理）的裁判模型依据论点质量做出裁决。在我们的框架中，专家模型仅为其确信正确的答案辩护，无需显式角色扮演，使辩论聚焦于专家意见分歧的实例。实验结果表明，辩论框架在多个多模态任务中均优于单个专家模型的表现。此外，较弱 LLM 的裁决可通过微调帮助视觉-语言模型建立推理能力。

> As Large Language Models (LLMs) gain expertise across diverse domains and modalities, scalable oversight becomes increasingly challenging, particularly when their capabilities may surpass human evaluators. Debate has emerged as a promising mechanism for enabling such oversight. In this work, we extend the debate paradigm to a multimodal setting, exploring its potential for weaker models to supervise and enhance the performance of stronger models. We focus on visual question answering (VQA), where two "sighted" expert vision-language models debate an answer, while a "blind" (text-only) judge adjudicates based solely on the quality of the arguments. In our framework, the experts defend only answers aligned with their beliefs, thereby obviating the need for explicit role-playing and concentrating the debate on instances of expert disagreement. Experiments on several multimodal tasks demonstrate that the debate framework consistently outperforms individual expert models. Moreover, judgments from weaker LLMs can help instill reasoning capabilities in vision-language models through finetuning.

[Arxiv](https://arxiv.org/abs/2505.14627)