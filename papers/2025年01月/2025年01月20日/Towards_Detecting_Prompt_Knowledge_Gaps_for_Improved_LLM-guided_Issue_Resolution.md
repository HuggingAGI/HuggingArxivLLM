# # 检测提示知识缺口：提升LLM引导问题解决的关键一步

发布时间：2025年01月20日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在软件开发中的应用，特别是如何通过分析开发人员与ChatGPT的对话来改进提示设计和问题解决效率。论文的重点在于如何通过识别和解决提示中的知识缺口来提高LLM在软件开发中的实际应用效果，因此属于LLM应用范畴。` `软件开发` `人机交互`

> Towards Detecting Prompt Knowledge Gaps for Improved LLM-guided Issue Resolution

# 摘要

> # 摘要
大型语言模型（LLMs）在软件开发中扮演着关键角色，尤其是在问题解决方面。然而，尽管LLMs被广泛应用，其在问题解决查询中的响应质量仍面临重大挑战。LLM交互常常产生错误、不完整或模糊的信息，这主要源于提示设计中的知识缺口，导致无效交流并降低开发效率。本文通过分析GitHub问题线程中的433个开发人员与ChatGPT的对话，探讨了提示知识缺口和对话风格对问题解决的影响。我们识别出开发人员提示中的四大知识缺口：上下文缺失、规范缺失、多重上下文和指令不明确。假设已关闭问题中的对话有助于成功解决问题，而未关闭问题中的对话则不然，我们发现无效对话中54.7%的提示存在知识缺口，而有效对话中仅有13.2%。此外，我们观察到七种不同的对话风格，其中指令提示、思维链和响应反馈最为常见。知识缺口存在于所有对话风格中，上下文缺失是开发人员在问题解决对话中最常遇到的挑战。基于分析，我们确定了与成功问题关闭相关的关键文本和代码启发式方法——具体性、上下文丰富性和清晰性——这些方法有助于评估提示质量。这些启发式方法为自动化工具奠定了基础，该工具能够动态标记不明确的提示并建议结构化改进。为验证可行性，我们开发了一个轻量级浏览器扩展原型，用于检测提示缺口，并可轻松集成到开发人员工作流程的其他工具中。

> Large language models (LLMs) have become essential in software development, especially for issue resolution. However, despite their widespread use, significant challenges persist in the quality of LLM responses to issue resolution queries. LLM interactions often yield incorrect, incomplete, or ambiguous information, largely due to knowledge gaps in prompt design, which can lead to unproductive exchanges and reduced developer productivity. In this paper, we analyze 433 developer-ChatGPT conversations within GitHub issue threads to examine the impact of prompt knowledge gaps and conversation styles on issue resolution. We identify four main knowledge gaps in developer prompts: Missing Context, Missing Specifications, Multiple Context, and Unclear Instructions. Assuming that conversations within closed issues contributed to successful resolutions while those in open issues did not, we find that ineffective conversations contain knowledge gaps in 54.7% of prompts, compared to only 13.2% in effective ones. Additionally, we observe seven distinct conversational styles, with Directive Prompting, Chain of Thought, and Responsive Feedback being the most prevalent. We find that knowledge gaps are present in all styles of conversations, with Missing Context being the most repeated challenge developers face in issue-resolution conversations. Based on our analysis, we identify key textual and code related heuristics-Specificity, Contextual Richness, and Clarity-that are associated with successful issue closure and help assess prompt quality. These heuristics lay the foundation for an automated tool that can dynamically flag unclear prompts and suggest structured improvements. To test feasibility, we developed a lightweight browser extension prototype for detecting prompt gaps, that can be easily adapted to other tools within developer workflows.

[Arxiv](https://arxiv.org/abs/2501.11709)