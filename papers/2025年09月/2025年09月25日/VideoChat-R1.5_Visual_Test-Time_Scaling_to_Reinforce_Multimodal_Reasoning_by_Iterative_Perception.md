# VideoChat-R1.5：视觉测试时扩展——通过迭代感知强化多模态推理

发布时间：2025年09月25日

`LLM应用` `媒体与娱乐`

> VideoChat-R1.5: Visual Test-Time Scaling to Reinforce Multimodal Reasoning by Iterative Perception

# 摘要

> 激发多模态大型语言模型（MLLMs）的推理能力，是实现类人感知与理解的关键。现有方法大多借助LLM推理分析解析后的视觉信息，但往往受限于静态感知阶段。本文提出视觉测试时缩放（VTTS）——一种通过推理阶段的迭代感知来增强MLLMs推理能力的全新方法。VTTS模仿人类的层级注意力机制，在更新的文本预测引导下，逐步聚焦于高置信度的时空区域。具体而言，VTTS采用迭代感知（ITP）机制，融合强化学习与时空监督来优化推理过程。为支撑这一范式，我们还构建了VTTS-80K数据集，专门用于迭代感知研究。这些设计让MLLM可通过增加感知计算量来提升性能。大量实验证实，VTTS在各类任务与基准测试中均展现出优异的有效性和泛化能力。我们新研发的Videochat-R1.5模型性能显著提升：在15+涵盖视频对话、视频推理及时空感知的基准测试中，相较于Qwen2.5VL-3B、-7B等强基线模型，平均性能提升超5%。

> Inducing reasoning in multimodal large language models (MLLMs) is critical for achieving human-level perception and understanding. Existing methods mainly leverage LLM reasoning to analyze parsed visuals, often limited by static perception stages. This paper introduces Visual Test-Time Scaling (VTTS), a novel approach to enhance MLLMs' reasoning via iterative perception during inference. VTTS mimics humans' hierarchical attention by progressively refining focus on high-confidence spatio-temporal regions, guided by updated textual predictions. Specifically, VTTS employs an Iterative Perception (ITP) mechanism, incorporating reinforcement learning with spatio-temporal supervision to optimize reasoning. To support this paradigm, we also present VTTS-80K, a dataset tailored for iterative perception. These designs allows a MLLM to enhance its performance by increasing its perceptual compute. Extensive experiments validate VTTS's effectiveness and generalization across diverse tasks and benchmarks. Our newly introduced Videochat-R1.5 model has achieved remarkable improvements, with an average increase of over 5\%, compared to robust baselines such as Qwen2.5VL-3B and -7B, across more than 15 benchmarks that encompass video conversation, video reasoning, and spatio-temporal perception.

[Arxiv](https://arxiv.org/abs/2509.21100)