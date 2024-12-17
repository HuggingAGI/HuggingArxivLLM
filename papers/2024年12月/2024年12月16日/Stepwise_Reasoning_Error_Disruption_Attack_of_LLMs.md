# 大型语言模型的逐步推理错误破坏攻击

发布时间：2024年12月16日

`LLM应用` `语言模型` `推理任务`

> Stepwise Reasoning Error Disruption Attack of LLMs

# 摘要

> 大型语言模型（LLMs）在复杂推理任务中成绩斐然，但其推理过程的安全性和稳健性尚未被充分探究。现有的针对LLM推理的攻击受特定设置所限，或缺乏隐蔽性，从而限制了其可行性和通用性。为应对这些难题，我们提出了逐步推理错误干扰（SEED）攻击，它巧妙地在前序推理步骤中注入错误，诱导模型得出错误的后续推理和最终答案。与以往方法不同，SEED能适配零样本和少样本设置，保持自然的推理流程，并能在不修改指令的情况下秘密施行。在四个不同模型的四个数据集上开展的大量实验证实了SEED的有效性，揭示了LLMs在推理过程中易受干扰的脆弱之处。这些发现凸显了要更加重视LLM推理的稳健性，以保障实际应用中的安全性。

> Large language models (LLMs) have made remarkable strides in complex reasoning tasks, but their safety and robustness in reasoning processes remain underexplored. Existing attacks on LLM reasoning are constrained by specific settings or lack of imperceptibility, limiting their feasibility and generalizability. To address these challenges, we propose the Stepwise rEasoning Error Disruption (SEED) attack, which subtly injects errors into prior reasoning steps to mislead the model into producing incorrect subsequent reasoning and final answers. Unlike previous methods, SEED is compatible with zero-shot and few-shot settings, maintains the natural reasoning flow, and ensures covert execution without modifying the instruction. Extensive experiments on four datasets across four different models demonstrate SEED's effectiveness, revealing the vulnerabilities of LLMs to disruptions in reasoning processes. These findings underscore the need for greater attention to the robustness of LLM reasoning to ensure safety in practical applications.

[Arxiv](https://arxiv.org/abs/2412.11934)