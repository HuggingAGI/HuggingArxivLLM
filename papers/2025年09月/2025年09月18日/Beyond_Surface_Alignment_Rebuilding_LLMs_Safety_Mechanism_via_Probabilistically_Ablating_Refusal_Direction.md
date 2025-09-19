# # 超越表面对齐：通过概率性消融拒绝方向重构大型语言模型的安全机制

发布时间：2025年09月18日

`LLM应用` `基础理论`

> Beyond Surface Alignment: Rebuilding LLMs Safety Mechanism via Probabilistically Ablating Refusal Direction

# 摘要

> 越狱攻击对大型语言模型（LLMs）构成持续威胁。当前的安全对齐方法虽试图解决这些问题，却存在两大显著局限：安全对齐深度不足与内部防御机制不够稳健。这些局限使其易受预填充、拒绝方向操纵等对抗性攻击的影响。为此，我们提出DeepRefusal——一个能克服这些问题的稳健安全对齐框架。DeepRefusal迫使模型从越狱状态动态重建拒绝机制：具体而言，在微调阶段，我们通过跨层和跨token深度对拒绝方向进行概率性消融，实现了这一目标。该方法不仅能有效防御预填充和拒绝方向攻击，还对其他未见过的越狱策略展现出强大韧性。在四个开源LLM系列和六种代表性攻击上的大量实验表明，DeepRefusal能将攻击成功率降低约95%，同时仅以极小的性能损失保持模型能力。

> Jailbreak attacks pose persistent threats to large language models (LLMs). Current safety alignment methods have attempted to address these issues, but they experience two significant limitations: insufficient safety alignment depth and unrobust internal defense mechanisms. These limitations make them vulnerable to adversarial attacks such as prefilling and refusal direction manipulation. We introduce DeepRefusal, a robust safety alignment framework that overcomes these issues. DeepRefusal forces the model to dynamically rebuild its refusal mechanisms from jailbreak states. This is achieved by probabilistically ablating the refusal direction across layers and token depths during fine-tuning. Our method not only defends against prefilling and refusal direction attacks but also demonstrates strong resilience against other unseen jailbreak strategies. Extensive evaluations on four open-source LLM families and six representative attacks show that DeepRefusal reduces attack success rates by approximately 95%, while maintaining model capabilities with minimal performance degradation.

[Arxiv](https://arxiv.org/abs/2509.15202)