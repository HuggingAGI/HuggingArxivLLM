# AutoPatent: 自动专利生成的多智能体框架

发布时间：2024年12月12日

`Agent

理由：这篇论文提出了一个名为AutoPatent的多代理框架，结合了基于LLM的规划代理、写作代理和审查代理，用于生成复杂的专利文件。虽然论文中提到了LLM的应用，但其核心在于多代理系统的设计和实现，因此更适合归类为Agent。` `专利处理`

> AutoPatent: A Multi-Agent Framework for Automatic Patent Generation

# 摘要

> 随着大型语言模型（LLMs）能力的不断提升，专利处理领域在自然语言处理社区中备受瞩目。然而，现有研究多集中于分类任务（如专利分类和审查）或短文本生成任务（如专利摘要和专利问答）。本文提出了一项新颖且实用的任务——Draft2Patent，并推出了相应的D2P基准，挑战LLMs基于初始草稿生成平均17K词的全长专利。由于专利的专业性、标准化术语和广泛长度，它们对LLMs构成了巨大挑战。为此，我们提出了一个名为AutoPatent的多代理框架，结合基于LLM的规划代理、写作代理和审查代理，利用PGTree和RRAG技术，生成长篇、复杂且高质量的完整专利文件。实验结果表明，AutoPatent框架显著提升了各类LLMs生成全面专利的能力。此外，我们发现，基于Qwen2.5-7B模型的AutoPatent框架生成的专利，在客观指标和人类评估中均优于GPT-4o、Qwen2.5-72B和LLAMA3.1-70B等更强大的LLMs生成的专利。我们将在接受后提供数据和代码，网址为url{https://github.com/QiYao-Wang/AutoPatent}。

> As the capabilities of Large Language Models (LLMs) continue to advance, the field of patent processing has garnered increased attention within the natural language processing community. However, the majority of research has been concentrated on classification tasks, such as patent categorization and examination, or on short text generation tasks like patent summarization and patent quizzes. In this paper, we introduce a novel and practical task known as Draft2Patent, along with its corresponding D2P benchmark, which challenges LLMs to generate full-length patents averaging 17K tokens based on initial drafts. Patents present a significant challenge to LLMs due to their specialized nature, standardized terminology, and extensive length. We propose a multi-agent framework called AutoPatent which leverages the LLM-based planner agent, writer agents, and examiner agent with PGTree and RRAG to generate lengthy, intricate, and high-quality complete patent documents. The experimental results demonstrate that our AutoPatent framework significantly enhances the ability to generate comprehensive patents across various LLMs. Furthermore, we have discovered that patents generated solely with the AutoPatent framework based on the Qwen2.5-7B model outperform those produced by larger and more powerful LLMs, such as GPT-4o, Qwen2.5-72B, and LLAMA3.1-70B, in both objective metrics and human evaluations. We will make the data and code available upon acceptance at url{https://github.com/QiYao-Wang/AutoPatent}.

[Arxiv](https://arxiv.org/abs/2412.09796)