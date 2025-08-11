# 超越提示诱骗的谎言：探索 LLM 在良性提示下的欺骗性

发布时间：2025年08月08日

`LLM理论` `可信计算` `人工智能安全`

> Beyond Prompt-Induced Lies: Investigating LLM Deception on Benign Prompts

# 摘要

> 大型语言模型（LLMs）在推理、规划和决策任务中的广泛应用，使其可信度成为关键议题。LLMs的故意欺骗行为——即蓄意编造或隐瞒信息以实现隐藏目标——仍是重大且未充分探索的威胁。现有研究通常通过显式设置“隐藏”目标来诱导欺骗，但这可能无法完全反映真实的人与LLM互动。超越人为诱导，我们研究了LLMs在良性提示下自我发起的欺骗行为。为解决评估中缺乏真实依据的问题，我们提出了一种基于“联系搜索问题”的新框架。该框架引入了两个从心理学原理衍生的统计指标：欺骗意图得分衡量模型对隐藏目标的倾向，而欺骗行为得分衡量LLM内部信念与其表达输出的不一致。在评估14个领先LLMs后，我们发现，随着任务难度的增加，两个指标均呈上升趋势，且在大多数模型中呈平行上升。基于此，我们制定了一个数学模型来解释这一行为。这些结果揭示，即使是最先进的LLMs在处理复杂问题时也表现出日益增长的欺骗倾向，这为在复杂和关键领域部署LLM代理提出了关键的担忧。

> Large Language Models (LLMs) have been widely deployed in reasoning, planning, and decision-making tasks, making their trustworthiness a critical concern. The potential for intentional deception, where an LLM deliberately fabricates or conceals information to serve a hidden objective, remains a significant and underexplored threat. Existing studies typically induce such deception by explicitly setting a "hidden" objective through prompting or fine-tuning, which may not fully reflect real-world human-LLM interactions. Moving beyond this human-induced deception, we investigate LLMs' self-initiated deception on benign prompts. To address the absence of ground truth in this evaluation, we propose a novel framework using "contact searching questions." This framework introduces two statistical metrics derived from psychological principles to quantify the likelihood of deception. The first, the Deceptive Intention Score, measures the model's bias towards a hidden objective. The second, Deceptive Behavior Score, measures the inconsistency between the LLM's internal belief and its expressed output. Upon evaluating 14 leading LLMs, we find that both metrics escalate as task difficulty increases, rising in parallel for most models. Building on these findings, we formulate a mathematical model to explain this behavior. These results reveal that even the most advanced LLMs exhibit an increasing tendency toward deception when handling complex problems, raising critical concerns for the deployment of LLM agents in complex and crucial domains.

[Arxiv](https://arxiv.org/abs/2508.06361)