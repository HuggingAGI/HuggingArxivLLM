# # 监督微调：让LLMs在编程教育中担任教学代理

发布时间：2025年02月27日

`LLM应用` `编程教育`

> Supervised Fine-Tuning LLMs to Behave as Pedagogical Agents in Programming Education

# 摘要

> 大型语言模型（LLMs）在高等教育中的应用日益受到关注，但其作为教学工具的有效性仍有待深入研究。本文介绍了GuideLM的开发，这是一种专为编程教育设计的微调大型语言模型。GuideLM已集成到调试C编译器（DCC）中，这是一个教育型C编译器，利用LLMs生成具有教学意义的错误解释。此前，DCC依赖现成的OpenAI模型，尽管这些模型准确，但常常过度辅助学生，直接提供解决方案，与预期的引导式教学相悖。
为解决这一问题，我们在包含528个学生问题/教师答案的 dataset 上进行了有监督微调（SFT），创建了两个模型：GuideLM 和 GuideLM-mini，分别在 ChatGPT-4o 和 4o-mini 上进行微调。我们对每个模型的400个响应进行了专家分析，比较了它们的教学效果与基础 OpenAI 模型。我们的评估基于建构主义和认知负荷理论，考察了概念支架、清晰度和苏格拉底式引导等因素。
结果显示，GuideLM 和 GuideLM-mini 在教学性能上有所提升，苏格拉底式引导方面比 GPT-4o 提高了8%，在用词经济性方面提升了58%。然而，这种改进是以略微降低一般准确性为代价的。尽管仍需进一步研究，但我们的发现表明，使用有针对性的数据集对 LLMs 进行微调是开发更适合教育环境的模型的有前途的方法。


> Large language models (LLMs) are increasingly being explored in higher education, yet their effectiveness as teaching agents remains underexamined. In this paper, we present the development of GuideLM, a fine-tuned LLM designed for programming education. GuideLM has been integrated into the Debugging C Compiler (DCC), an educational C compiler that leverages LLMs to generate pedagogically sound error explanations. Previously, DCC relied on off-the-shelf OpenAI models, which, while accurate, often over-assisted students by directly providing solutions despite contrary prompting.
  To address this, we employed supervised fine-tuning (SFT) on a dataset of 528 student-question/teacher-answer pairs, creating two models: GuideLM and GuideLM-mini, fine-tuned on ChatGPT-4o and 4o-mini, respectively. We conducted an expert analysis of 400 responses per model, comparing their pedagogical effectiveness against base OpenAI models. Our evaluation, grounded in constructivism and cognitive load theory, assessed factors such as conceptual scaffolding, clarity, and Socratic guidance.
  Results indicate that GuideLM and GuideLM-mini improve pedagogical performance, with an 8% increase in Socratic guidance and a 58% improvement in economy of words compared to GPT-4o. However, this refinement comes at the cost of a slight reduction in general accuracy. While further work is needed, our findings suggest that fine-tuning LLMs with targeted datasets is a promising approach for developing models better suited to educational contexts.

[Arxiv](https://arxiv.org/abs/2502.20527)