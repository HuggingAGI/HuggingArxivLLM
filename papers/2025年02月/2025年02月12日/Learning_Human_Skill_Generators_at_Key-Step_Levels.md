# 在关键步骤上学习人类技能生成器

发布时间：2025年02月12日

`LLM应用

论文摘要：我们专注于在关键步骤层面学习人类技能生成器。技能生成是一项极具挑战性的任务，但其成功实施将极大促进人类技能的学习，并为具身智能提供更多经验。尽管当前的视频生成模型能够合成简单且原子化的人类操作，但它们在处理复杂的人类技能时表现乏力。这是因为人类技能通常涉及多步骤、长时间的行动以及复杂的场景转换，而现有的简单自回归方法在合成长视频时无法有效生成人类技能。

为了解决这一问题，我们提出了一项新任务——关键步骤技能生成（KS-Gen），旨在降低生成人类技能视频的复杂性。给定初始状态和技能描述，任务要求生成完成该技能的关键步骤视频片段，而非完整的长视频。为了支持这一任务，我们引入了一个精心整理的数据集，并定义了多种评估指标来衡量性能。

考虑到KS-Gen的复杂性，我们为该任务设计了一个新的框架。首先，一个多模态大型语言模型（MLLM）通过检索参数生成关键步骤的描述。随后，我们使用关键步骤图像生成器（KIG）来解决技能视频中关键步骤之间的不连续性问题。最后，视频生成模型利用这些描述和关键步骤图像，生成具有高时间一致性的关键步骤视频片段。我们对结果进行了详细分析，希望能为人类技能生成提供更多见解。所有模型和数据均可在https://github.com/MCG-NJU/KS-Gen获取。

LLM应用` `视频生成` `计算机视觉`

> Learning Human Skill Generators at Key-Step Levels

# 摘要

> 我们专注于在关键步骤层面学习人类技能生成器。技能生成是一项极具挑战性的任务，但其成功实施将极大促进人类技能的学习，并为具身智能提供更多经验。尽管当前的视频生成模型能够合成简单且原子化的人类操作，但它们在处理复杂的人类技能时表现乏力。这是因为人类技能通常涉及多步骤、长时间的行动以及复杂的场景转换，而现有的简单自回归方法在合成长视频时无法有效生成人类技能。

为了解决这一问题，我们提出了一项新任务——关键步骤技能生成（KS-Gen），旨在降低生成人类技能视频的复杂性。给定初始状态和技能描述，任务要求生成完成该技能的关键步骤视频片段，而非完整的长视频。为了支持这一任务，我们引入了一个精心整理的数据集，并定义了多种评估指标来衡量性能。

考虑到KS-Gen的复杂性，我们为该任务设计了一个新的框架。首先，一个多模态大型语言模型（MLLM）通过检索参数生成关键步骤的描述。随后，我们使用关键步骤图像生成器（KIG）来解决技能视频中关键步骤之间的不连续性问题。最后，视频生成模型利用这些描述和关键步骤图像，生成具有高时间一致性的关键步骤视频片段。我们对结果进行了详细分析，希望能为人类技能生成提供更多见解。所有模型和数据均可在https://github.com/MCG-NJU/KS-Gen获取。

> We are committed to learning human skill generators at key-step levels. The generation of skills is a challenging endeavor, but its successful implementation could greatly facilitate human skill learning and provide more experience for embodied intelligence. Although current video generation models can synthesis simple and atomic human operations, they struggle with human skills due to their complex procedure process. Human skills involve multi-step, long-duration actions and complex scene transitions, so the existing naive auto-regressive methods for synthesizing long videos cannot generate human skills. To address this, we propose a novel task, the Key-step Skill Generation (KS-Gen), aimed at reducing the complexity of generating human skill videos. Given the initial state and a skill description, the task is to generate video clips of key steps to complete the skill, rather than a full-length video. To support this task, we introduce a carefully curated dataset and define multiple evaluation metrics to assess performance. Considering the complexity of KS-Gen, we propose a new framework for this task. First, a multimodal large language model (MLLM) generates descriptions for key steps using retrieval argument. Subsequently, we use a Key-step Image Generator (KIG) to address the discontinuity between key steps in skill videos. Finally, a video generation model uses these descriptions and key-step images to generate video clips of the key steps with high temporal consistency. We offer a detailed analysis of the results, hoping to provide more insights on human skill generation. All models and data are available at https://github.com/MCG-NJU/KS-Gen.

[Arxiv](https://arxiv.org/abs/2502.08234)