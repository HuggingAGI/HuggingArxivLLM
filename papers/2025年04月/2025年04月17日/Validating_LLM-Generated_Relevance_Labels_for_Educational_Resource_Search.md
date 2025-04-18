# # 验证大型语言模型生成的教育搜索相关性标签

发布时间：2025年04月17日

`LLM应用

这篇论文探讨了大型语言模型（LLMs）在评估教育资源相关性中的应用，属于LLM的实际应用领域。` `信息检索`

> Validating LLM-Generated Relevance Labels for Educational Resource Search

# 摘要

> 信息检索中的手动相关性判断不仅成本高昂，还需要专业知识，因此人们越来越倾向于使用大型语言模型（LLMs）来进行自动评估。尽管LLMs在通用网络搜索中展现出潜力，但它们在评估特定领域（如教育资源）搜索结果方面的有效性尚未得到充分研究。为了探索在LLM提示中融入特定领域标准的不同方法，我们从一项涉及教学专业人士执行与课程规划相关搜索任务的用户研究中收集并发布了一个包含401个人类相关性判断的数据集。我们比较了三种构建提示的方法：基于先前使用LLMs作为相关性判断器工作的简单两方面评估基线，从教育文献中得出的全面12维评分标准，以及直接由研究参与者提供的标准。通过使用特定领域的框架，LLMs与人类判断达成高度一致（Cohen's $κ$高达0.650），显著优于基线方法。由参与者得出的框架尤其稳健，GPT-3.5在10维和5维版本中分别达到了0.639和0.613的$κ$分数。系统级评估显示，LLM判断可靠地识别了表现最佳的检索方法（RBO分数0.71-0.76），同时在系统之间保持了合理的区分度（RBO 0.52-0.56）。这些发现表明，当使用特定领域标准提示时，LLMs可以有效地评估教育资源，尽管性能因框架复杂性和输入结构而异。

> Manual relevance judgements in Information Retrieval are costly and require expertise, driving interest in using Large Language Models (LLMs) for automatic assessment. While LLMs have shown promise in general web search scenarios, their effectiveness for evaluating domain-specific search results, such as educational resources, remains unexplored. To investigate different ways of including domain-specific criteria in LLM prompts for relevance judgement, we collected and released a dataset of 401 human relevance judgements from a user study involving teaching professionals performing search tasks related to lesson planning. We compared three approaches to structuring these prompts: a simple two-aspect evaluation baseline from prior work on using LLMs as relevance judges, a comprehensive 12-dimensional rubric derived from educational literature, and criteria directly informed by the study participants. Using domain-specific frameworks, LLMs achieved strong agreement with human judgements (Cohen's $κ$ up to 0.650), significantly outperforming the baseline approach. The participant-derived framework proved particularly robust, with GPT-3.5 achieving $κ$ scores of 0.639 and 0.613 for 10-dimension and 5-dimension versions respectively. System-level evaluation showed that LLM judgements reliably identified top-performing retrieval approaches (RBO scores 0.71-0.76) while maintaining reasonable discrimination between systems (RBO 0.52-0.56). These findings suggest that LLMs can effectively evaluate educational resources when prompted with domain-specific criteria, though performance varies with framework complexity and input structure.

[Arxiv](https://arxiv.org/abs/2504.12732)