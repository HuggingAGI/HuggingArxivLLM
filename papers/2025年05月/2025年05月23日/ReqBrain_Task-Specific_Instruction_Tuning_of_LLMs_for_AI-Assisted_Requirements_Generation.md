# ReqBrain：为AI辅助需求生成任务定制的LLMs指令微调方法

发布时间：2025年05月23日

`LLM应用` `需求工程` `软件工程`

> ReqBrain: Task-Specific Instruction Tuning of LLMs for AI-Assisted Requirements Generation

# 摘要

> 需求工程中的需求提取和规格说明仍是一项劳动密集型的手工流程，容易出现不一致和遗漏，这在现代软件工程中是一个重大挑战。近期研究表明，大型语言模型（LLMs）在自动化需求生成方面具有巨大潜力，从而支持需求提取和规格说明；然而，如何有效实现这一潜力仍是一个待解问题。在这项研究中，我们推出了ReqBrain（需求大脑），一款基于AI的工具，它借助经过微调的LLM生成真实且充分的软件需求。软件工程师可通过基于聊天的交互方式使用ReqBrain，自动完成需求生成并按类型分类。我们整理了一个符合ISO 29148标准的高质量需求数据集，并对五个7B参数的LLMs进行了微调，以确定ReqBrain的最佳基础模型。表现最佳的模型Zephyr-7b-beta在生成真实且充分需求方面表现出色，BERT得分为89.30%，FRUGAL得分为91.20。人工评估进一步证实了ReqBrain在需求生成方面的有效性。我们的研究结果表明，经过微调的生成式AI有可能显著提升需求提取和规格说明的质量，为未来扩展到缺陷识别、测试用例生成和敏捷用户故事创建奠定了基础。

> Requirements elicitation and specification remains a labor-intensive, manual process prone to inconsistencies and gaps, presenting a significant challenge in modern software engineering. Emerging studies underscore the potential of employing large language models (LLMs) for automated requirements generation to support requirements elicitation and specification; however, it remains unclear how to implement this effectively. In this work, we introduce ReqBrain, an Al-assisted tool that employs a fine-tuned LLM to generate authentic and adequate software requirements. Software engineers can engage with ReqBrain through chat-based sessions to automatically generate software requirements and categorize them by type. We curated a high-quality dataset of ISO 29148-compliant requirements and fine-tuned five 7B-parameter LLMs to determine the most effective base model for ReqBrain. The top-performing model, Zephyr-7b-beta, achieved 89.30\% Fl using the BERT score and a FRUGAL score of 91.20 in generating authentic and adequate requirements. Human evaluations further confirmed ReqBrain's effectiveness in generating requirements. Our findings suggest that generative Al, when fine-tuned, has the potential to improve requirements elicitation and specification, paving the way for future extensions into areas such as defect identification, test case generation, and agile user story creation.

[Arxiv](https://arxiv.org/abs/2505.17632)