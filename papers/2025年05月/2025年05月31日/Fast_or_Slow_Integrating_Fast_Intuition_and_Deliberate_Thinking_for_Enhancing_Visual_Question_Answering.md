# 快还是慢？融合快速直觉与深思熟虑的思考，助力视觉问答能力提升

发布时间：2025年05月31日

`LLM应用` `视觉问答` `多模态模型`

> Fast or Slow? Integrating Fast Intuition and Deliberate Thinking for Enhancing Visual Question Answering

# 摘要

> 多模态大型语言模型 (MLLMs) 在视觉问答 (VQA) 任务中仍显不足。尽管当前方法通过引入视觉提示取得了进展，但我们的研究揭示了关键限制：这些方法对每个视觉问题无差别标注所有检测到的对象，生成过多的视觉标记，从而降低任务性能。这一问题主要源于对关键视觉元素关注不足，引发两个重要问题：所有对象是否同等重要？所有问题是否都需要视觉提示？

受二元认知理论启发，该理论区分了人类推理中的本能与审慎认知模式，我们提出 FOCUS，一种即插即用的方法，动态适应问题复杂性，结合快速直觉判断与审慎分析推理，以提升 MLLM 的视觉语言推理能力。对于简单问题，FOCUS 支持高效的零样本推理。对于复杂任务，它采用“先概念化后观察”策略，突出关键元素。

在 ScienceQA、TextQA、VizWiz 和 MME 四个基准上的广泛实验表明，FOCUS 一致提升开源和黑箱 MLLMs 的性能，在所有数据集上实现显著增益。消融研究进一步证实，结合多样化的认知策略与精细的视觉信息对优异性能的重要性。代码即将发布。


> Multimodal large language models (MLLMs) still struggle with complex reasoning tasks in Visual Question Answering (VQA). While current methods have advanced by incorporating visual prompts, our study uncovers critical limitations: these approaches indiscriminately annotate all detected objects for every visual question, generating excessive visual markers that degrade task performance. This issue stems primarily from a lack of focus on key visual elements, raising two important questions: Are all objects equally important, and do all questions require visual prompts? Motivated by Dual Process Theory, which distinguishes between instinctive and deliberate cognitive modes in human reasoning, we propose FOCUS, a plug-and-play approach that dynamically adapts to the complexity of questions, combining fast intuitive judgments with deliberate analytical reasoning to enhance the vision-language reasoning capability of the MLLM. For straightforward questions, FOCUS supports efficient zero-shot reasoning. For more complex tasks, it employs the conceptualizing before observation strategy to highlight critical elements. Extensive experiments on four benchmarks, ScienceQA, TextQA, VizWiz, and MME, demonstrate that FOCUS consistently improves the performance of both open-source and black-box MLLMs, achieving significant gains across all datasets. Ablation studies further validate the importance of combining diverse cognitive strategies with refined visual information for superior performance. Code will be released.

[Arxiv](https://arxiv.org/abs/2506.00806)