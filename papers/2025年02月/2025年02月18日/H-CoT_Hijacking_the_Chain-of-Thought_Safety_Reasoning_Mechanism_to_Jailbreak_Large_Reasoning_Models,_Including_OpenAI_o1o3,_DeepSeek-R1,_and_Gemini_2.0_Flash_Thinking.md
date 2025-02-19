# # 摘要  
H-CoT：利用思维链安全推理机制突破大型推理模型限制，涵盖 OpenAI o1/o3、DeepSeek-R1 与 Gemini 2.0 闪念推理

发布时间：2025年02月18日

`LLM应用` `人工智能安全`

> H-CoT: Hijacking the Chain-of-Thought Safety Reasoning Mechanism to Jailbreak Large Reasoning Models, Including OpenAI o1/o3, DeepSeek-R1, and Gemini 2.0 Flash Thinking

# 摘要

> 大型推理模型（LRMs）在安全检查领域展现了强大的推理能力，通过链式思考推理来判断是否回应请求。虽然这一方法在平衡模型效用与安全性方面极具潜力，但其鲁棒性仍待深入研究。为解决这一问题，我们推出了Malicious-Educator基准，该基准将危险或恶意请求伪装成看似合法的教育提示。实验结果显示，包括OpenAI o1/o3、DeepSeek-R1和Gemini 2.0 Flash Thinking在内的主流商业级LRMs存在严重安全漏洞。例如，OpenAI的o1模型虽最初保持约98%的高拒绝率，但更新后安全性显著下降；而攻击者可轻松从DeepSeek-R1和Gemini 2.0 Flash Thinking中提取犯罪策略。为凸显这些漏洞，我们提出Hijacking Chain-of-Thought（H-CoT），这是一种通用且可转移的攻击方法，通过利用模型自身展示的中间推理来破解其安全机制。在H-CoT的影响下，拒绝率骤降——从98%降至2%以下——甚至使原本谨慎的模型转变为主动提供有害内容。我们希望这些发现能强调构建更强大安全机制的紧迫性，以确保先进推理能力的同时，不妥协道德标准。

> Large Reasoning Models (LRMs) have recently extended their powerful reasoning capabilities to safety checks-using chain-of-thought reasoning to decide whether a request should be answered. While this new approach offers a promising route for balancing model utility and safety, its robustness remains underexplored. To address this gap, we introduce Malicious-Educator, a benchmark that disguises extremely dangerous or malicious requests beneath seemingly legitimate educational prompts. Our experiments reveal severe security flaws in popular commercial-grade LRMs, including OpenAI o1/o3, DeepSeek-R1, and Gemini 2.0 Flash Thinking. For instance, although OpenAI's o1 model initially maintains a high refusal rate of about 98%, subsequent model updates significantly compromise its safety; and attackers can easily extract criminal strategies from DeepSeek-R1 and Gemini 2.0 Flash Thinking without any additional tricks. To further highlight these vulnerabilities, we propose Hijacking Chain-of-Thought (H-CoT), a universal and transferable attack method that leverages the model's own displayed intermediate reasoning to jailbreak its safety reasoning mechanism. Under H-CoT, refusal rates sharply decline-dropping from 98% to below 2%-and, in some instances, even transform initially cautious tones into ones that are willing to provide harmful content. We hope these findings underscore the urgent need for more robust safety mechanisms to preserve the benefits of advanced reasoning capabilities without compromising ethical standards.

[Arxiv](https://arxiv.org/abs/2502.12893)