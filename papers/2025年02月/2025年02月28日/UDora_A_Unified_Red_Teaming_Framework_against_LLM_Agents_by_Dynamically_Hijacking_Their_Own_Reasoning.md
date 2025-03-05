# UDora：一种针对LLM智能体的统一红队框架，通过动态劫持其自身推理能力

发布时间：2025年02月28日

`LLM应用` `金融科技` `信息安全`

> UDora: A Unified Red Teaming Framework against LLM Agents by Dynamically Hijacking Their Own Reasoning

# 摘要

> 配备外部工具的大型语言模型（LLM）代理在处理复杂任务（如网络购物、自动回复邮件和金融交易）方面表现出色。然而，这些进展也带来了新的风险：当LLM代理能够访问敏感的外部功能时，对抗攻击的可能性显著增加。由于LLM代理在执行最终行动之前会进行广泛的推理或规划，因此操纵它们执行特定的恶意行为或调用特定工具仍然是一项重大挑战。因此，传统的对抗攻击方法，如直接在恶意指令中嵌入对抗字符串或在工具交互中注入恶意提示，对现代LLM代理的效果有限。

为了解决这一问题，我们提出了UDora——一个专门用于LLM代理的统一红队框架。UDora通过动态利用代理自身的推理过程，迫使它执行恶意行为。具体来说，UDora首先对给定任务的模型推理进行采样，然后自动识别推理轨迹中多个最优位置以插入有针对性的扰动。随后，它使用修改后的推理作为目标来优化对抗字符串。通过反复应用此过程，LLM代理将被诱导执行指定的恶意行动或调用特定的恶意工具。实验结果表明，与现有方法相比，我们的方法在三个LLM代理数据集上表现出更优越的有效性。

> Large Language Model (LLM) agents equipped with external tools have become increasingly powerful for handling complex tasks such as web shopping, automated email replies, and financial trading. However, these advancements also amplify the risks of adversarial attacks, particularly when LLM agents can access sensitive external functionalities. Moreover, because LLM agents engage in extensive reasoning or planning before executing final actions, manipulating them into performing targeted malicious actions or invoking specific tools remains a significant challenge. Consequently, directly embedding adversarial strings in malicious instructions or injecting malicious prompts into tool interactions has become less effective against modern LLM agents. In this work, we present UDora, a unified red teaming framework designed for LLM Agents that dynamically leverages the agent's own reasoning processes to compel it toward malicious behavior. Specifically, UDora first samples the model's reasoning for the given task, then automatically identifies multiple optimal positions within these reasoning traces to insert targeted perturbations. Subsequently, it uses the modified reasoning as the objective to optimize the adversarial strings. By iteratively applying this process, the LLM agent will then be induced to undertake designated malicious actions or to invoke specific malicious tools. Our approach demonstrates superior effectiveness compared to existing methods across three LLM agent datasets.

[Arxiv](https://arxiv.org/abs/2503.01908)