# 基于心智理论的自动化元提示设计

发布时间：2025年05月13日

`LLM应用`

> Automated Meta Prompt Engineering for Alignment with the Theory of Mind

# 摘要

> 我们提出了一种元提示方法，旨在在处理复杂任务时生成流畅文本，同时优化人类心理预期与大型语言模型 (LLM) 神经处理之间的神经状态相似性。我们引入了一种智能体强化学习技术，其中作为裁判的 LLM (LLMaaJ) 通过上下文学习，教导另一台 LLM 如何通过解析生成文本的预期和非预期特征来创建内容。为了衡量人们对内容生产的心理预期，用户在 2024 美国网球公开赛期间对长篇 AI 生成的文章进行了修改。如今，LLMaaJ 可以通过在文本生成过程中预判和纳入人工修改，解决心智理论 (ToM) 对齐问题。通过实验和对实时生产系统的分析，人类内容审核员的期望与 AI 的一致性达到了 53.8%，平均迭代次数为 4.38 次。在希尔伯特向量空间中对内容特征（如事实性、新颖性、重复性和相关性）进行几何解释，结合了所有特征重要性（空间体积）和个体特征相关性（顶点对齐），使 LLMaaJ 能够优化人类心智理论。这通过扩展网球赛事的报道范围，提升了内容质量。我们在 2024 美国网球公开赛中部署的工作，已在体育和娱乐领域的其他实时活动中得到应用。

> We introduce a method of meta-prompting that jointly produces fluent text for complex tasks while optimizing the similarity of neural states between a human's mental expectation and a Large Language Model's (LLM) neural processing. A technique of agentic reinforcement learning is applied, in which an LLM as a Judge (LLMaaJ) teaches another LLM, through in-context learning, how to produce content by interpreting the intended and unintended generated text traits. To measure human mental beliefs around content production, users modify long form AI-generated text articles before publication at the US Open 2024 tennis Grand Slam. Now, an LLMaaJ can solve the Theory of Mind (ToM) alignment problem by anticipating and including human edits within the creation of text from an LLM. Throughout experimentation and by interpreting the results of a live production system, the expectations of human content reviewers had 100% of alignment with AI 53.8% of the time with an average iteration count of 4.38. The geometric interpretation of content traits such as factualness, novelty, repetitiveness, and relevancy over a Hilbert vector space combines spatial volume (all trait importance) with vertices alignment (individual trait relevance) enabled the LLMaaJ to optimize on Human ToM. This resulted in an increase in content quality by extending the coverage of tennis action. Our work that was deployed at the US Open 2024 has been used across other live events within sports and entertainment.

[Arxiv](https://arxiv.org/abs/2505.09024)