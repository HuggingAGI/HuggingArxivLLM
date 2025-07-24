# 让自我改进的智能体在测试时借助人机交互指导进行学习

发布时间：2025年07月22日

`Agent` `风险管理`

> Enabling Self-Improving Agents to Learn at Test Time With Human-In-The-Loop Guidance

# 摘要

> 大型语言模型 (LLM) 代理在合规性要求和用户风险筛查等动态变化的环境中常常表现吃力。当前的离线微调和标准提示方法由于无法在实际运行中有效适应新知识，因此显得力不从心。为了解决这一问题，我们提出了自适应反思交互式代理 (ARIA)，一个专门设计用于在测试时持续学习最新领域知识的 LLM 代理框架。

ARIA 通过结构化的自我对话评估自身的不确定性，主动识别知识缺口，并向人类专家请求针对性的解释或修正。随后，它会系统地更新内部的时间戳知识库，并通过比较和澄清查询来检测和解决冲突或过时的知识。

我们在 TikTok Pay 的实际客户尽职调查名称筛查任务上评估了 ARIA，同时测试了公开可用的动态知识任务。结果表明，与使用标准离线微调和现有自我改进代理的基线相比，ARIA 在适应性和准确性方面都有显著提升。ARIA 已在 TikTok Pay 部署，服务于超过 1.5 亿月活跃用户，证实了其在快速变化环境中实际运营中的实用性和有效性。

> Large language model (LLM) agents often struggle in environments where rules and required domain knowledge frequently change, such as regulatory compliance and user risk screening. Current approaches, like offline fine-tuning and standard prompting, are insufficient because they cannot effectively adapt to new knowledge during actual operation. To address this limitation, we propose the Adaptive Reflective Interactive Agent (ARIA), an LLM agent framework designed specifically to continuously learn updated domain knowledge at test time. ARIA assesses its own uncertainty through structured self-dialogue, proactively identifying knowledge gaps and requesting targeted explanations or corrections from human experts. It then systematically updates an internal, timestamped knowledge repository with provided human guidance, detecting and resolving conflicting or outdated knowledge through comparisons and clarification queries. We evaluate ARIA on the realistic customer due diligence name screening task on TikTok Pay, alongside publicly available dynamic knowledge tasks. Results demonstrate significant improvements in adaptability and accuracy compared to baselines using standard offline fine-tuning and existing self-improving agents. ARIA is deployed within TikTok Pay serving over 150 million monthly active users, confirming its practicality and effectiveness for operational use in rapidly evolving environments.

[Arxiv](https://arxiv.org/abs/2507.17131)