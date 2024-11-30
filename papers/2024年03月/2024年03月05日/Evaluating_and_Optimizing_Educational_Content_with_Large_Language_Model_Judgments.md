# 利用大型语言模型评判来评估与优化教育内容，以提升教学质量及效果。

发布时间：2024年03月05日

`LLM应用`

> Evaluating and Optimizing Educational Content with Large Language Model Judgments

# 摘要

> 制作高效的教育素材往往耗时费力，需深入研究学生学习成效。为突破这一瓶颈，有人设想构建学生学习的计算模型以优化教学内容，但认知学习过程难以准确建模。我们另辟蹊径，提议运用语言模型（LMs）作为教育专家，通过它们评估各类教学指导对学生学习成果的影响。具体来说，我们采用 GPT-3.5 来度量教学材料对不同学生群体整体学习效果的影响，并成功验证其能再现如“专家反转效应”和“变异性效应”等经典教育学理论。这揭示了 LMs 在评估教育资源可靠性方面的巨大潜能。在此基础上，我们创新提出一种教学指导优化策略，让一个 LM 根据另一个 LM 的评价结果生成教学内容，将其评价视为奖励函数。我们运用此法创作了旨在最大化学生学习进步的数学应用题练习册，并邀请人类教师对其进行评价。结果显示，LM 的评价与人类教师的喜好高度吻合。最后，我们探讨了人类观点与 LM 意见之间可能出现的分歧及其在自动教学设计过程中可能导致的隐患。

> Creating effective educational materials generally requires expensive and time-consuming studies of student learning outcomes. To overcome this barrier, one idea is to build computational models of student learning and use them to optimize instructional materials. However, it is difficult to model the cognitive processes of learning dynamics. We propose an alternative approach that uses Language Models (LMs) as educational experts to assess the impact of various instructions on learning outcomes. Specifically, we use GPT-3.5 to evaluate the overall effect of instructional materials on different student groups and find that it can replicate well-established educational findings such as the Expertise Reversal Effect and the Variability Effect. This demonstrates the potential of LMs as reliable evaluators of educational content. Building on this insight, we introduce an instruction optimization approach in which one LM generates instructional materials using the judgments of another LM as a reward function. We apply this approach to create math word problem worksheets aimed at maximizing student learning gains. Human teachers' evaluations of these LM-generated worksheets show a significant alignment between the LM judgments and human teacher preferences. We conclude by discussing potential divergences between human and LM opinions and the resulting pitfalls of automating instructional design.

[Arxiv](https://arxiv.org/abs/2403.02795)