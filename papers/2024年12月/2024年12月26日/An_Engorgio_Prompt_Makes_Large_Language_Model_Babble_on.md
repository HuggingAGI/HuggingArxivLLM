# Engorgio 提示让大语言模型滔滔不绝

发布时间：2024年12月26日

`LLM理论

理由：这篇论文主要探讨了自回归大型语言模型（LLMs）在推理成本攻击中的脆弱性，并提出了一种新的方法（Engorgio）来生成对抗性提示，以增加推理过程的计算成本和延迟。论文的核心在于对LLMs的理论分析，特别是其推理过程的自回归特性和对抗性攻击的机制。因此，这篇论文更适合归类为LLM理论，因为它主要关注LLMs的理论特性和潜在的安全隐患，而不是具体的应用或实现。` `网络安全` `人工智能`

> An Engorgio Prompt Makes Large Language Model Babble on

# 摘要

> 自回归大型语言模型（LLMs）在众多实际任务中表现卓越，但其新范式也带来了新的安全隐患。本文深入探讨了LLMs对推理成本攻击的脆弱性，即恶意用户通过精心设计的Engorgio提示，故意增加推理过程的计算成本和延迟。我们创新性地提出了Engorgio方法，旨在高效生成对抗性Engorgio提示，从而影响目标LLM的服务可用性。Engorgio的两大技术亮点在于：(1) 采用参数化分布追踪LLMs的预测轨迹；(2) 针对LLMs推理过程的自回归特性，提出新颖的损失函数，稳定抑制<EOS>标记的出现，防止其打断LLM的生成过程。我们在13个开源LLMs上进行了广泛实验，参数范围从125M到30B。实验结果显示，Engorgio提示能成功诱导LLMs生成异常冗长的输出（在达到输出长度限制90%+时，耗时约为2-13倍），在白盒场景下，我们的真实世界实验进一步验证了Engergio对计算资源有限的LLM服务的潜在威胁。代码已开源，访问地址：https://github.com/jianshuod/Engorgio-prompt。

> Auto-regressive large language models (LLMs) have yielded impressive performance in many real-world tasks. However, the new paradigm of these LLMs also exposes novel threats. In this paper, we explore their vulnerability to inference cost attacks, where a malicious user crafts Engorgio prompts to intentionally increase the computation cost and latency of the inference process. We design Engorgio, a novel methodology, to efficiently generate adversarial Engorgio prompts to affect the target LLM's service availability. Engorgio has the following two technical contributions. (1) We employ a parameterized distribution to track LLMs' prediction trajectory. (2) Targeting the auto-regressive nature of LLMs' inference process, we propose novel loss functions to stably suppress the appearance of the <EOS> token, whose occurrence will interrupt the LLM's generation process. We conduct extensive experiments on 13 open-sourced LLMs with parameters ranging from 125M to 30B. The results show that Engorgio prompts can successfully induce LLMs to generate abnormally long outputs (i.e., roughly 2-13$\times$ longer to reach 90%+ of the output length limit) in a white-box scenario and our real-world experiment demonstrates Engergio's threat to LLM service with limited computing resources. The code is accessible at https://github.com/jianshuod/Engorgio-prompt.

[Arxiv](https://arxiv.org/abs/2412.19394)