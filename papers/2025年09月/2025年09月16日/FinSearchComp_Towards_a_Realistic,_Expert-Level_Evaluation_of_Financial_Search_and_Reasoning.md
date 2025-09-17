# FinSearchComp：致力于金融搜索与推理的真实专家级评估

发布时间：2025年09月16日

`Agent` `金融科技`

> FinSearchComp: Towards a Realistic, Expert-Level Evaluation of Financial Search and Reasoning

# 摘要

> 搜索已成为基于LLM智能体的核心基础设施，也是迈向更通用智能的关键一环。金融领域尤其考验实力：分析师需频繁对时效性强的专业数据开展复杂的多步骤搜索，因此成为评估搜索能力与知识锚定推理的绝佳场景。但现有开放金融数据集均未评估端到端智能体的数据搜索能力，这主要是因为构建真实复杂的任务需要深厚金融专业知识，而时效性数据的评估难度也很大。为此，我们推出了FinSearchComp——首个面向真实开放域金融搜索与推理的全开源智能体基准。该基准涵盖三项任务——时效性数据获取、简单历史查询与复杂历史调查——均高度还原了金融分析师的真实工作流程。为确保任务难度与可靠性，我们特邀70位金融专业人士参与标注，并搭建了严格的多阶段质量控制体系。该基准包含635道题目，覆盖全球及大中华区市场，并在该基准上对21款模型（产品）进行了测试。Grok 4（网络版）在全球市场子集表现最佳，准确率接近专家水平；豆包（网络版）则在大中华区子集位居榜首。实验分析显示，为智能体接入网络搜索与金融插件可显著提升在FinSearchComp上的表现，而模型与工具的国家背景也对性能产生显著影响。通过贴合分析师真实工作场景并支持端到端评估，FinSearchComp为复杂金融搜索与推理提供了专业且高难度的评测基准。

> Search has emerged as core infrastructure for LLM-based agents and is widely viewed as critical on the path toward more general intelligence. Finance is a particularly demanding proving ground: analysts routinely conduct complex, multi-step searches over time-sensitive, domain-specific data, making it ideal for assessing both search proficiency and knowledge-grounded reasoning. Yet no existing open financial datasets evaluate data searching capability of end-to-end agents, largely because constructing realistic, complicated tasks requires deep financial expertise and time-sensitive data is hard to evaluate. We present FinSearchComp, the first fully open-source agent benchmark for realistic, open-domain financial search and reasoning. FinSearchComp comprises three tasks -- Time-Sensitive Data Fetching, Simple Historical Lookup, and Complex Historical Investigation -- closely reproduce real-world financial analyst workflows. To ensure difficulty and reliability, we engage 70 professional financial experts for annotation and implement a rigorous multi-stage quality-assurance pipeline. The benchmark includes 635 questions spanning global and Greater China markets, and we evaluate 21 models (products) on it. Grok 4 (web) tops the global subset, approaching expert-level accuracy. DouBao (web) leads on the Greater China subset. Experimental analyses show that equipping agents with web search and financial plugins substantially improves results on FinSearchComp, and the country origin of models and tools impact performance significantly.By aligning with realistic analyst tasks and providing end-to-end evaluation, FinSearchComp offers a professional, high-difficulty testbed for complex financial search and reasoning.

[Arxiv](https://arxiv.org/abs/2509.13160)