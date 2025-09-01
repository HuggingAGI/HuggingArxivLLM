# # 警惕“第三只眼”！MLLM驱动的智能手机智能体隐私意识基准测试

发布时间：2025年08月26日

`Agent` `基础理论`

> Mind the Third Eye! Benchmarking Privacy Awareness in MLLM-powered Smartphone Agents

# 摘要

> 智能手机在为用户带来极大便利的同时，也让设备得以广泛记录各类个人信息。现有的多模态大型语言模型（MLLMs）驱动的智能手机智能体，在自动化各类任务上已展现出卓越性能。然而，这也带来了代价——这些智能体在运行过程中被赋予了访问用户敏感个人信息的大量权限。为深入探究这些智能体的隐私意识，我们首次（据我们所知）构建了一个涵盖7138个场景的大规模基准测试集。此外，针对场景中的隐私上下文，我们还标注了其类型（如账户凭证）、敏感级别及位置信息。随后，我们对七个主流的现有智能手机智能体开展了细致的基准测试。结果显示，几乎所有被测智能体的隐私意识（RA）都不尽如人意——即便给出明确提示，其表现仍低于60%。总体来看，闭源智能体的隐私保护能力优于开源智能体，而Gemini 2.0-flash表现最优，RA达67%。我们还发现，智能体的隐私检测能力与场景敏感级别密切相关：敏感级别越高的场景，往往越容易被识别。我们希望这些发现能启发研究界重新审视智能手机智能体在实用性与隐私保护之间的失衡权衡问题。相关代码与基准测试集已开源，地址为https://zhixin-l.github.io/SAPA-Bench。

> Smartphones bring significant convenience to users but also enable devices to extensively record various types of personal information. Existing smartphone agents powered by Multimodal Large Language Models (MLLMs) have achieved remarkable performance in automating different tasks. However, as the cost, these agents are granted substantial access to sensitive users' personal information during this operation. To gain a thorough understanding of the privacy awareness of these agents, we present the first large-scale benchmark encompassing 7,138 scenarios to the best of our knowledge. In addition, for privacy context in scenarios, we annotate its type (e.g., Account Credentials), sensitivity level, and location. We then carefully benchmark seven available mainstream smartphone agents. Our results demonstrate that almost all benchmarked agents show unsatisfying privacy awareness (RA), with performance remaining below 60% even with explicit hints. Overall, closed-source agents show better privacy ability than open-source ones, and Gemini 2.0-flash achieves the best, achieving an RA of 67%. We also find that the agents' privacy detection capability is highly related to scenario sensitivity level, i.e., the scenario with a higher sensitivity level is typically more identifiable. We hope the findings enlighten the research community to rethink the unbalanced utility-privacy tradeoff about smartphone agents. Our code and benchmark are available at https://zhixin-l.github.io/SAPA-Bench.

[Arxiv](https://arxiv.org/abs/2508.19493)