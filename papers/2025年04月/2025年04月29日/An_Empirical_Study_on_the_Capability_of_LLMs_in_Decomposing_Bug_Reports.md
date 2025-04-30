# # 大型语言模型分解错误报告能力的实证研究

发布时间：2025年04月29日

`LLM应用` `软件工程`

> An Empirical Study on the Capability of LLMs in Decomposing Bug Reports

# 摘要

> # 背景与目标  
软件开发过程中，bug报告扮演着关键角色。它们帮助开发人员追踪和修复问题，但复杂的报告往往难以处理，导致修复延迟并影响软件质量。本研究旨在探索大型语言模型（LLMs）能否协助开发人员，将复杂的bug报告自动分解为更小、独立的单元，从而更易于理解和处理。  

# 研究方法  
我们从Apache Jira收集了127个已解决的隐私相关bug报告，并进行了实证研究。采用不同的提示策略，我们评估了ChatGPT和DeepSeek的表现。首先，使用零-shot提示测试两种模型，随后通过包含演示的改进提示（少-shot策略）来衡量它们在bug分解方面的潜力。  

# 实验结果  
研究发现，LLMs在分解bug报告方面具有能力，但整体表现仍有待提升，且高度依赖提示的质量。在零-shot提示下，ChatGPT和DeepSeek的表现均不理想。经过提示优化后，ChatGPT的真实分解率提高了140%，DeepSeek更是提升了163.64%。  

# 结论  
LLMs在帮助开发人员分析和分解复杂bug报告方面展现出潜力，但准确性和对bug的理解能力仍需进一步提升。

> Background: Bug reports are essential to the software development life cycle. They help developers track and resolve issues, but are often difficult to process due to their complexity, which can delay resolution and affect software quality. Aims: This study investigates whether large language models (LLMs) can assist developers in automatically decomposing complex bug reports into smaller, self-contained units, making them easier to understand and address. Method: We conducted an empirical study on 127 resolved privacy-related bug reports collected from Apache Jira. We evaluated ChatGPT and DeepSeek using different prompting strategies. We first tested both LLMs with zero-shot prompts, then applied improved prompts with demonstrations (using few-shot prompting) to measure their abilities in bug decomposition. Results: Our findings show that LLMs are capable of decomposing bug reports, but their overall performance still requires further improvement and strongly depends on the quality of the prompts. With zero-shot prompts, both studied LLMs (ChatGPT and DeepSeek) performed poorly. After prompt tuning, ChatGPT's true decomposition rate increased by 140\% and DeepSeek's by 163.64\%. Conclusions: LLMs show potential in helping developers analyze and decompose complex bug reports, but they still need improvement in terms of accuracy and bug understanding.

[Arxiv](https://arxiv.org/abs/2504.20911)