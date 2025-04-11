# 物体如何助力视频语言理解？

发布时间：2025年04月10日

`LLM应用` `视频理解` `问答系统`

> How Can Objects Help Video-Language Understanding?

# 摘要

> 多模态大型语言模型（MLLMs）如何感知视觉世界仍是一个未解之谜。在一种极端情况下，物体和关系的建模可能隐式地通过归纳偏置实现，例如将物体视为令牌。在另一种极端情况下，实证结果揭示了一个惊人发现：仅执行视觉描述，倾向于忽略物体的空间配置，却成为视频理解的强大基线。我们旨在回答：在多模态模型中，物体如何助力视频语言理解？我们从物体表征和适应性两个角度来探讨这一问题。具体而言，我们研究表征表达能力（例如分布式与符号化）与集成难度（例如学习适配器时的数据效率）之间的权衡。通过在五个视频问答数据集上的广泛评估，我们证实了显式集成基于物体的表征仍然必要，且符号化物体最易于集成，同时在问答任务中表现出色。我们希望我们的发现能激励社区探索将感知模块显式整合到多模态模型设计中。我们的代码和模型将公开发布。


> How multimodal large language models (MLLMs) perceive the visual world remains a mystery. To one extreme, object and relation modeling may be implicitly implemented with inductive biases, for example by treating objects as tokens. To the other extreme, empirical results reveal the surprising finding that simply performing visual captioning, which tends to ignore spatial configuration of the objects, serves as a strong baseline for video understanding. We aim to answer the question: how can objects help video-language understanding in MLLMs? We tackle the question from the object representation and adaptation perspectives. Specifically, we investigate the trade-off between representation expressiveness (e.g., distributed versus symbolic) and integration difficulty (e.g., data-efficiency when learning the adapters). Through extensive evaluations on five video question answering datasets, we confirm that explicit integration of object-centric representation remains necessary, and the symbolic objects can be most easily integrated while being performant for question answering. We hope our findings can encourage the community to explore the explicit integration of perception modules into MLLM design. Our code and models will be publicly released.

[Arxiv](https://arxiv.org/abs/2504.07454)