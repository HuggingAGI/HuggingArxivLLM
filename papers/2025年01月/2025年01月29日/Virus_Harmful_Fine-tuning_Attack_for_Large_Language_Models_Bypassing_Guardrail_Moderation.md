# 病毒：绕过护栏审核的大型语言模型有害微调攻击

发布时间：2025年01月29日

`LLM理论

理由：这篇论文主要讨论了大型语言模型（LLMs）在微调过程中面临的安全问题，特别是针对有害微调攻击的防护措施的有效性。论文提出了新的攻击方法（Virus攻击），并分析了现有防护措施的局限性。这些内容属于对LLM安全性和理论层面的探讨，因此分类为“LLM理论”。` `人工智能` `网络安全`

> Virus: Harmful Fine-tuning Attack for Large Language Models Bypassing Guardrail Moderation

# 摘要

> 最新研究表明，大型语言模型（LLMs）易受有害微调攻击，微调少量有害样本后，模型会丧失安全对齐能力。为降低风险，通常会在微调前使用防护栏过滤有害样本。然而，我们通过设计新的红队方法发现，仅依赖防护栏进行数据过滤并不可靠。我们提出的Virus攻击方法，通过轻微修改有害数据，轻松绕过防护栏审核。实验显示，Virus优化的有害数据在防护栏中无法被检测，泄漏率高达100%，且攻击效果显著。本文的核心观点是：	extbf{将防护栏审核视为应对有害微调攻击的救命稻草是鲁莽的}，因为它无法解决预训练LLMs的固有安全问题。代码已开源：https://github.com/git-disl/Virus。

> Recent research shows that Large Language Models (LLMs) are vulnerable to harmful fine-tuning attacks -- models lose their safety alignment ability after fine-tuning on a few harmful samples. For risk mitigation, a guardrail is typically used to filter out harmful samples before fine-tuning. By designing a new red-teaming method, we in this paper show that purely relying on the moderation guardrail for data filtration is not reliable. Our proposed attack method, dubbed Virus, easily bypasses the guardrail moderation by slightly modifying the harmful data. Experimental results show that the harmful data optimized by Virus is not detectable by the guardrail with up to 100\% leakage ratio, and can simultaneously achieve superior attack performance. Finally, the key message we want to convey through this paper is that: \textbf{it is reckless to consider guardrail moderation as a clutch at straws towards harmful fine-tuning attack}, as it cannot solve the inherent safety issue of the pre-trained LLMs. Our code is available at https://github.com/git-disl/Virus

[Arxiv](https://arxiv.org/abs/2501.17433)