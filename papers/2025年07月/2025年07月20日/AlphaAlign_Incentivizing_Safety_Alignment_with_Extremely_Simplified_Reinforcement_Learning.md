# AlphaAlign：以极简强化学习激励安全对齐

发布时间：2025年07月20日

`LLM理论` `内容安全`

> AlphaAlign: Incentivizing Safety Alignment with Extremely Simplified Reinforcement Learning

# 摘要

> 尽管大型语言模型（LLMs）从其庞大的预训练数据中具备潜在的安全理解能力，但它们仍然容易生成有害内容，并在安全对齐后表现出过度拒绝和效用下降等问题。当前的安全对齐方法通常导致表面化的拒绝捷径，或者依赖于基于推理方法的密集监督，未能充分利用模型内在的安全自我意识。我们提出了一种名为	extbf{AlphaAlign}的简单而有效的纯强化学习（RL）框架，该框架设计了可验证的安全奖励机制，旨在通过主动安全推理激发这种潜在的安全意识。AlphaAlign采用双奖励机制：一方面，通过可验证的安全奖励鼓励对有害查询进行格式正确且理由明确的拒绝，同时对过度拒绝行为进行惩罚；另一方面，借助标准化的帮助奖励引导模型对良性输入生成高质量的响应。这使模型能够在无需依赖监督式安全特定推理数据的情况下，发展出主动安全推理能力。AlphaAlign展现了三大核心优势：（1）简洁高效，仅需二元提示安全标签和少量RL步骤即可实现显著改进；（2）打破安全与效用的权衡，通过增强对有害内容的拒绝并减少过度拒绝，同时保持甚至提升一般任务性能和对未知越狱攻击的鲁棒性；（3）深度对齐，培养主动安全推理能力，生成明确的安全理由，而非依赖浅层拒绝模式。

> Large language models (LLMs), despite possessing latent safety understanding from their vast pretraining data, remain vulnerable to generating harmful content and exhibit issues such as over-refusal and utility degradation after safety alignment. Current safety alignment methods often result in superficial refusal shortcuts or rely on intensive supervision for reasoning-based approaches, failing to fully leverage the model's intrinsic safety self-awareness. We propose \textbf{AlphaAlign}, a simple yet effective pure reinforcement learning (RL) framework with verifiable safety reward designed to incentivize this latent safety awareness through proactive safety reasoning.} AlphaAlign employs a dual-reward system: a verifiable safety reward encourages correctly formatted and explicitly justified refusals for harmful queries while penalizing over-refusals, and a normalized helpfulness reward guides high-quality responses to benign inputs. This allows the model to develop proactive safety reasoning capabilities without depending on supervised safety-specific reasoning data. AlphaAlign demonstrates three key advantages: (1) Simplicity and efficiency, requiring only binary prompt safety labels and minimal RL steps for substantial improvements. (2) Breaking the safety-utility trade-off, by enhancing refusal of harmful content and reducing over-refusals, while simultaneously maintaining or even improving general task performance and robustness to unseen jailbreaks. (3) Deep alignment, fostering proactive safety reasoning that generates explicit safety rationales rather than relying on shallow refusal patterns.

[Arxiv](https://arxiv.org/abs/2507.14987)