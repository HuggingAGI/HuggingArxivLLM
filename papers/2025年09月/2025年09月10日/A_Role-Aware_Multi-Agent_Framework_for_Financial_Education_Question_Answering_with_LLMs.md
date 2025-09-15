# 一种面向金融教育问答的角色感知多智能体框架：基于大型语言模型（LLMs）

发布时间：2025年09月10日

`Agent` `金融科技` `教育科技`

> A Role-Aware Multi-Agent Framework for Financial Education Question Answering with LLMs

# 摘要

> 问答（QA）在金融教育中至关重要，但现有大型语言模型（LLM）常难以捕捉金融解题所需的精细化专业推理。金融领域要求多步骤定量分析能力、精通专业术语，还要能理解现实场景。为此，我们提出一种多智能体框架，通过基于角色的提示策略提升特定领域问答任务的表现。该框架包含基础生成器、证据检索器和专家评审器三个智能体，通过单次迭代协作生成优化答案。我们在在线学习平台Study.com的3532道专家设计的金融教育题目上对该框架进行了评估：利用检索增强生成（RAG）从6本金融教材中提取上下文证据，并为领域专家评审器设计提示策略。实验结果显示，基于批判的答案优化策略相较于零样本思维链基线，准确率提升了6.6%-8.3%，其中Gemini-2.0-Flash模型表现最优。此外，该方法还能让GPT-4o-mini的性能媲美经过金融领域微调的FinGPT-mt_Llama3-8B_LoRA模型。研究结果表明，这种经济高效的方法能有效提升金融问答质量，同时为多智能体金融LLM系统的后续研究提供了启示。

> Question answering (QA) plays a central role in financial education, yet existing large language model (LLM) approaches often fail to capture the nuanced and specialized reasoning required for financial problem-solving. The financial domain demands multistep quantitative reasoning, familiarity with domain-specific terminology, and comprehension of real-world scenarios. We present a multi-agent framework that leverages role-based prompting to enhance performance on domain-specific QA. Our framework comprises a Base Generator, an Evidence Retriever, and an Expert Reviewer agent that work in a single-pass iteration to produce a refined answer. We evaluated our framework on a set of 3,532 expert-designed finance education questions from Study.com, an online learning platform. We leverage retrieval-augmented generation (RAG) for contextual evidence from 6 finance textbooks and prompting strategies for a domain-expert reviewer. Our experiments indicate that critique-based refinement improves answer accuracy by 6.6-8.3% over zero-shot Chain-of-Thought baselines, with the highest performance from Gemini-2.0-Flash. Furthermore, our method enables GPT-4o-mini to achieve performance comparable to the finance-tuned FinGPT-mt_Llama3-8B_LoRA. Our results show a cost-effective approach to enhancing financial QA and offer insights for further research in multi-agent financial LLM systems.

[Arxiv](https://arxiv.org/abs/2509.09727)