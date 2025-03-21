# 代码审查问答评估：大型语言模型的代码审查理解

发布时间：2025年03月20日

`LLM应用` `软件工程` `代码生成`

> CodeReviewQA: The Code Review Comprehension Assessment for Large Language Models

# 摘要

> 当前大型语言模型（LLMs）在代码生成方面表现优异，但在处理现实世界中的软件工程任务，如根据代码审查意见修改源代码时，仍显不足，限制了其实际应用。代码审查评论通常隐含、模糊且口语化，要求模型同时理解代码和人类意图。这一挑战促使我们评估大型语言模型在技术与对话情境之间架起桥梁的能力。虽然现有研究采用了自动代码精炼（ACR）任务来解决这些问题，但目前的评估方法仍显不足，主要依赖于文本匹配指标，这些指标难以深入揭示模型失败的原因，且容易受到训练数据污染的影响。为了解决这些问题，我们引入了一个全新的评估基准——【数学公式】，它使我们能够进行细致入微的能力评估，并降低数据污染的风险。在CodeReviewQA中，我们将代码精炼的生成任务分解为【数学公式】：【数学公式】（CTR）、【数学公式】（CL）和【数学公式】（SI）。每一步都被重新表述为难度各异的多项选择题，从而能够精准评估模型的能力，同时降低数据污染的风险。我们的全面评估涵盖了9种编程语言的900个手动精选高质量示例上的72个近期发布的大型语言模型。结果显示，CodeReviewQA能够揭示模型在代码审查理解方面的具体弱点，这些弱点与它们在生成式自动代码精炼任务中的表现相互独立。

> State-of-the-art large language models (LLMs) have demonstrated impressive code generation capabilities but struggle with real-world software engineering tasks, such as revising source code to address code reviews, hindering their practical use. Code review comments are often implicit, ambiguous, and colloquial, requiring models to grasp both code and human intent. This challenge calls for evaluating large language models' ability to bridge both technical and conversational contexts. While existing work has employed the automated code refinement (ACR) task to resolve these comments, current evaluation methods fall short, relying on text matching metrics that provide limited insight into model failures and remain susceptible to training data contamination. To address these limitations, we introduce a novel evaluation benchmark, $\textbf{CodeReviewQA}$ that enables us to conduct fine-grained assessment of model capabilities and mitigate data contamination risks. In CodeReviewQA, we decompose the generation task of code refinement into $\textbf{three essential reasoning steps}$: $\textit{change type recognition}$ (CTR), $\textit{change localisation}$ (CL), and $\textit{solution identification}$ (SI). Each step is reformulated as multiple-choice questions with varied difficulty levels, enabling precise assessment of model capabilities, while mitigating data contamination risks. Our comprehensive evaluation spans 72 recently released large language models on $\textbf{900 manually curated, high-quality examples}$ across nine programming languages. Our results show that CodeReviewQA is able to expose specific model weaknesses in code review comprehension, disentangled from their generative automated code refinement results.

[Arxiv](https://arxiv.org/abs/2503.16167)