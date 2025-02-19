# # 标题  
BoT: 利用后门攻击破解 o1 类大型语言模型的长推理过程

发布时间：2025年02月16日

`LLM理论` `人工智能` `网络安全`

> BoT: Breaking Long Thought Processes of o1-like Large Language Models through Backdoor Attack

# 摘要

> 更长的思考，更好的表现：具有深度推理能力的大型语言模型，特别是 o1-like 模型，通过在推理过程中生成广泛的思考过程，展现出了卓越的性能。然而，这一优势也带来了一个潜在的漏洞：攻击者可以通过迫使模型立即响应而无需思考过程来削弱其性能。针对这一问题，本文提出了一种针对 o1-like 模型长思考过程的新型攻击场景，并提出了 BoT（Break CoT），这是一种通过后门攻击选择性破坏模型内在推理机制的方法。BoT 通过设计触发器构建中毒数据集，并通过监督微调或直接偏好优化注入后门。当触发器被激活时，模型直接生成答案而无需思考过程，同时对干净输入仍保持正常的推理能力。在开源 o1-like 模型上的广泛实验，包括最近的 DeepSeek-R1，表明 BoT 几乎实现了高攻击成功率，同时保持了干净输入的准确性，凸显了当前模型中存在的关键安全风险。此外，任务难度与有用性之间的关系揭示了一种潜在的良好应用，使用户能够根据任务复杂性自定义模型行为。代码可在 \href{https://github.com/zihao-ai/BoT}{https://github.com/zihao-ai/BoT} 获取。

> Longer thought, better performance: large language models with deep reasoning capabilities, particularly o1-like models, have demonstrated remarkable performance by generating extensive thought processes during inference. This trade-off reveals a potential vulnerability: adversaries could compromise model performance by forcing immediate responses without thought processes. To this end, in this paper, we introduce a novel attack scenario targeting the long thought processes of o1-like models and propose BoT (Break CoT), which can selectively break intrinsic reasoning mechanisms through backdoor attacks. BoT constructs poisoned datasets with designed triggers and injects backdoor by either supervised fine-tuning or direct preference optimization. When triggered, the model directly generates answers without thought processes, while maintaining normal reasoning capabilities for clean inputs. Extensive experiments on open-source o1-like models, including recent DeepSeek-R1, demonstrate that BoT nearly achieves high attack success rates while maintaining clean accuracy, highlighting the critical safety risk in current models. Furthermore, the relationship between task difficulty and helpfulness reveals a potential application for good, enabling users to customize model behavior based on task complexity. Code is available at \href{https://github.com/zihao-ai/BoT}{https://github.com/zihao-ai/BoT}.

[Arxiv](https://arxiv.org/abs/2502.12202)