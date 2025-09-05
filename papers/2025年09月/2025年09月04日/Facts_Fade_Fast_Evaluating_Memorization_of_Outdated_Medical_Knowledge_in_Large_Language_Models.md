# 事实转瞬即逝：评估大型语言模型对过时医学知识的记忆

发布时间：2025年09月04日

`LLM应用` `医疗健康`

> Facts Fade Fast: Evaluating Memorization of Outdated Medical Knowledge in Large Language Models

# 摘要

> 大型语言模型（LLMs）能力的不断增强，为辅助医学研究人员和医生、提升医疗服务水平展现了巨大潜力。然而，医疗建议会随着新研究和新进展不断更新，LLMs对静态训练数据的依赖因此成为一大隐患。一旦LLMs记住过时的医学知识，就可能给出有害建议，或在临床推理任务中出错。为探究这一问题，我们基于系统综述构建了两个全新的问答（QA）数据集：MedRevQA（包含16,501个QA对，覆盖通用生物医学知识）和MedChangeQA（512个QA对的子集，聚焦随时间变化的医学共识）。我们在这些数据集上对八个主流LLM进行了评估，结果显示所有模型都存在一致依赖过时知识的问题。我们还分析了过时预训练数据和训练策略对这一现象的影响，进而提出了未来的改进方向，为开发更及时、更可靠的医疗AI系统奠定了基础。

> The growing capabilities of Large Language Models (LLMs) show significant potential to enhance healthcare by assisting medical researchers and physicians. However, their reliance on static training data is a major risk when medical recommendations evolve with new research and developments. When LLMs memorize outdated medical knowledge, they can provide harmful advice or fail at clinical reasoning tasks. To investigate this problem, we introduce two novel question-answering (QA) datasets derived from systematic reviews: MedRevQA (16,501 QA pairs covering general biomedical knowledge) and MedChangeQA (a subset of 512 QA pairs where medical consensus has changed over time). Our evaluation of eight prominent LLMs on the datasets reveals consistent reliance on outdated knowledge across all models. We additionally analyze the influence of obsolete pre-training data and training strategies to explain this phenomenon and propose future directions for mitigation, laying the groundwork for developing more current and reliable medical AI systems.

[Arxiv](https://arxiv.org/abs/2509.04304)