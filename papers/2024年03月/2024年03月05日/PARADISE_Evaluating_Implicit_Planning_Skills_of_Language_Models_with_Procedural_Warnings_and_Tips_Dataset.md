# PARADISE 是一项研究，它借助程序性警告和提示数据集来评估语言模型在隐式规划任务上的表现能力。

发布时间：2024年03月05日

`Agent`

> PARADISE: Evaluating Implicit Planning Skills of Language Models with Procedural Warnings and Tips Dataset

# 摘要

> 近期，学界对大型语言模型能否进行计划制定及执行的探讨日益升温。然而，以往多数研究仅让LLM在简单化场景下生成高层次计划，忽略了语言复杂度和领域多样性，使得其规划能力的深入分析受限。这些研究框架局限了评价方式（如预设动作空间）和架构选项（如仅采用生成模型），并忽视了进行真实世界分析时至关重要的语言细节。为此，我们引入了一个名为PARADISE的任务，它以wikiHow来源的实际操作文本为基础，采取问答形式进行演绎推理。该任务要求模型根据明确的目标直接推断警告和提示信息，无需经过中间步骤，以此检验模型能否仅从目标中推断出计划中的隐含知识。通过使用微调后的语言模型和零样本提示技术，实验结果显示，在大多数情况下，针对特定任务的小型模型比大型语言模型表现更优。尽管技术有所进步，但所有模型仍无法媲美人类的表现。此外，我们的分析还揭示了若干引人入胜的见解，如关键词缺失时模型行为的差异、BERT家族和GPT-4在应对物理及抽象目标时的挑战，以及本研究所提出的任务能为其他未遇见过的程序性任务提供宝贵的前期知识储备。现可公开获取PARADISE数据集及相关资源，以便进一步研究，访问链接为https://github.com/GGLAB-KU/paradise。

> Recently, there has been growing interest within the community regarding whether large language models are capable of planning or executing plans. However, most prior studies use LLMs to generate high-level plans for simplified scenarios lacking linguistic complexity and domain diversity, limiting analysis of their planning abilities. These setups constrain evaluation methods (e.g., predefined action space), architectural choices (e.g., only generative models), and overlook the linguistic nuances essential for realistic analysis. To tackle this, we present PARADISE, an abductive reasoning task using Q\&A format on practical procedural text sourced from wikiHow. It involves warning and tip inference tasks directly associated with goals, excluding intermediary steps, with the aim of testing the ability of the models to infer implicit knowledge of the plan solely from the given goal. Our experiments, utilizing fine-tuned language models and zero-shot prompting, reveal the effectiveness of task-specific small models over large language models in most scenarios. Despite advancements, all models fall short of human performance. Notably, our analysis uncovers intriguing insights, such as variations in model behavior with dropped keywords, struggles of BERT-family and GPT-4 with physical and abstract goals, and the proposed tasks offering valuable prior knowledge for other unseen procedural tasks. The PARADISE dataset and associated resources are publicly available for further research exploration with https://github.com/GGLAB-KU/paradise.

[Arxiv](https://arxiv.org/abs/2403.03167)