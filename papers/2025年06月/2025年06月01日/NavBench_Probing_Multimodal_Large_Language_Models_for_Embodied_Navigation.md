# # **NavBench**：探查多模态大语言模型的具身导航能力

发布时间：2025年06月01日

`LLM应用` `机器人导航`

> NavBench: Probing Multimodal Large Language Models for Embodied Navigation

# 摘要

> 多模态大型语言模型（MLLMs）在视觉语言任务中表现优异，但它们在具身环境中的理解和行动能力仍有待深入探索。我们推出NavBench，这是一个评估MLLMs在零样本设置下具身导航能力的基准。NavBench包含两个核心部分：（1）导航理解，通过三项基于认知的任务进行评估，包括全局指令对齐、时间进度估计和局部观察-动作推理，涵盖3,200个问答对；（2）在72个室内场景中的432个episode中进行逐步执行，按空间、认知和执行复杂性分层。为了支持实际部署，我们设计了一条将MLLMs输出转换为机器人动作的流水线。我们评估了多种专有和开源模型，发现GPT-4o在各项任务中表现突出，而较轻量的开源模型在简单情况下也能成功。研究结果表明，理解能力较强的模型往往能实现更好的执行性能。提供基于地图的上下文可以显著提高决策准确性，特别是在中等难度的场景中。然而，大多数模型在时间理解方面仍存在困难，尤其是在导航过程中估计进度，这可能成为未来研究的关键挑战。

> Multimodal Large Language Models (MLLMs) have demonstrated strong generalization in vision-language tasks, yet their ability to understand and act within embodied environments remains underexplored. We present NavBench, a benchmark to evaluate the embodied navigation capabilities of MLLMs under zero-shot settings. NavBench consists of two components: (1) navigation comprehension, assessed through three cognitively grounded tasks including global instruction alignment, temporal progress estimation, and local observation-action reasoning, covering 3,200 question-answer pairs; and (2) step-by-step execution in 432 episodes across 72 indoor scenes, stratified by spatial, cognitive, and execution complexity. To support real-world deployment, we introduce a pipeline that converts MLLMs' outputs into robotic actions. We evaluate both proprietary and open-source models, finding that GPT-4o performs well across tasks, while lighter open-source models succeed in simpler cases. Results also show that models with higher comprehension scores tend to achieve better execution performance. Providing map-based context improves decision accuracy, especially in medium-difficulty scenarios. However, most models struggle with temporal understanding, particularly in estimating progress during navigation, which may pose a key challenge.

[Arxiv](https://arxiv.org/abs/2506.01031)