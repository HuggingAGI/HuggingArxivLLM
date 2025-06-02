# Pangu DeepDiver：通过开放网络强化学习实现自适应搜索强度缩放

发布时间：2025年05月30日

`LLM应用

理由：这篇论文主要探讨了大型语言模型在信息检索任务中的应用，特别是通过强化学习框架DeepDiver提升模型的搜索强度缩放能力。它引入了新的数据集和方法，属于LLM的应用层面研究。` `信息检索` `问答系统`

> Pangu DeepDiver: Adaptive Search Intensity Scaling via Open-Web Reinforcement Learning

# 摘要

> 信息检索需要迭代的证据收集和反思性推理，但大型语言模型（LLMs）在开放网络问答任务中仍面临挑战。现有方法依赖静态提示规则或基于维基百科的训练，这限制了其在真实网络环境中应对模糊性、矛盾证据和噪声的能力。这些受限的训练设置阻碍了LLMs学习动态决定何时何地搜索，以及如何根据信息需求调整搜索深度和频率。我们将这种缺失的能力定义为搜索强度缩放（SIS），即在模糊或矛盾条件下增强搜索努力的新兴技能，而不是停留在过度自信且未经充分验证的答案上。

为了研究SIS，我们推出了WebPuzzle，这是首个专注于开放互联网环境信息检索的数据集。WebPuzzle包含24K训练实例和275个测试问题，涵盖基于维基和开放网络的查询。基于此数据集，我们提出了DeepDiver，一个通过在现实开放网络环境中鼓励自适应搜索策略来促进SIS的强化学习（RL）框架。实验结果表明，借助DeepDiver增强的Pangu-7B-Reasoner在真实网络任务中的表现可与拥有6710亿参数的DeepSeek-R1相媲美。我们详细介绍了DeepDiver从冷启动监督微调到精心设计的RL阶段的训练课程，并展示了其SIS能力不仅限于封闭问答，还能扩展到长文本写作等开放式任务。我们的研究推动了LLMs在自适应信息检索方面的发展，并为未来研究提供了宝贵的基准和数据集。

> Information seeking demands iterative evidence gathering and reflective reasoning, yet large language models (LLMs) still struggle with it in open-web question answering. Existing methods rely on static prompting rules or training with Wikipedia-based corpora and retrieval environments, limiting adaptability to the real-world web environment where ambiguity, conflicting evidence, and noise are prevalent. These constrained training settings hinder LLMs from learning to dynamically decide when and where to search, and how to adjust search depth and frequency based on informational demands. We define this missing capacity as Search Intensity Scaling (SIS)--the emergent skill to intensify search efforts under ambiguous or conflicting conditions, rather than settling on overconfident, under-verification answers.
  To study SIS, we introduce WebPuzzle, the first dataset designed to foster information-seeking behavior in open-world internet environments. WebPuzzle consists of 24K training instances and 275 test questions spanning both wiki-based and open-web queries. Building on this dataset, we propose DeepDiver, a Reinforcement Learning (RL) framework that promotes SIS by encouraging adaptive search policies through exploration under a real-world open-web environment. Experimental results show that Pangu-7B-Reasoner empowered by DeepDiver achieve performance on real-web tasks comparable to the 671B-parameter DeepSeek-R1. We detail DeepDiver's training curriculum from cold-start supervised fine-tuning to a carefully designed RL phase, and present that its capability of SIS generalizes from closed-form QA to open-ended tasks such as long-form writing. Our contributions advance adaptive information seeking in LLMs and provide a valuable benchmark and dataset for future research.

[Arxiv](https://arxiv.org/abs/2505.24332)