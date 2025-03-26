# Decorum：基于语言的室内3D场景风格条件生成方法

发布时间：2025年03月25日

`LLM应用` `室内设计` `3D建模`

> Decorum: A Language-Based Approach For Style-Conditioned Synthesis of Indoor 3D Scenes

# 摘要

> 3D室内场景生成对数字与现实环境设计至关重要。为了实现这一过程的自动化，场景生成模型不仅要能生成合理的布局，还需兼顾视觉特征与风格偏好。现有方法在这些方面控制有限，仅支持简单的对象描述或空间关系作为文本输入。我们的方法Decorum通过在各阶段采用语言表示，让用户能以自然语言控制生成过程。这使我们得以利用大型语言模型（LLMs）在语言映射上的最新成果。此外，我们发现基于文本的表示结合多模态LLMs的新对象检索方法，能有效为场景选择家具。在3D-FRONT基准数据集上的评估显示，我们的方法在文本引导的场景合成与对象检索方面优于现有方案。

> 3D indoor scene generation is an important problem for the design of digital and real-world environments. To automate this process, a scene generation model should be able to not only generate plausible scene layouts, but also take into consideration visual features and style preferences. Existing methods for this task exhibit very limited control over these attributes, only allowing text inputs in the form of simple object-level descriptions or pairwise spatial relationships. Our proposed method Decorum enables users to control the scene generation process with natural language by adopting language-based representations at each stage. This enables us to harness recent advancements in Large Language Models (LLMs) to model language-to-language mappings. In addition, we show that using a text-based representation allows us to select furniture for our scenes using a novel object retrieval method based on multimodal LLMs. Evaluations on the benchmark 3D-FRONT dataset show that our methods achieve improvements over existing work in text-conditioned scene synthesis and object retrieval.

[Arxiv](https://arxiv.org/abs/2503.18155)