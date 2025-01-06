# 逻辑反制：通过对比问题探索模型防御机制

发布时间：2025年01月03日

`LLM理论

理由：这篇论文主要探讨了大型语言模型在推理能力方面的漏洞，并提出了一种新的越狱技术（POATE）来诱导模型生成不道德响应。论文还评估了现有防御措施的不足，并提出了一种新的防御策略。这些内容主要涉及大型语言模型的理论研究，特别是其推理能力和安全机制的改进，因此应归类为LLM理论。` `人工智能` `网络安全`

> Turning Logic Against Itself : Probing Model Defenses Through Contrastive Questions

# 摘要

> 尽管大型语言模型在人类价值观和伦理准则对齐方面取得了显著进展，但它们仍难以抵御利用其推理能力的复杂越狱攻击。传统安全机制多聚焦于显性恶意意图的检测，而忽视了更深层次的漏洞。本文提出了一种名为POATE（极性相反查询生成、对抗性模板构建与详细阐述）的越狱技术，通过对比推理诱导模型生成不道德响应。POATE生成语义相反的提示，并结合对抗性模板，巧妙引导模型输出有害内容。我们在LLaMA3、Gemma2、Phi3和GPT-4等六个不同参数规模的语言模型家族上进行了广泛评估，证明该攻击具有显著鲁棒性，攻击成功率（约44%）远超现有方法。我们还评估了七种安全防御措施，发现它们在应对基于推理的漏洞时存在明显不足。为此，我们提出了一种防御策略，通过链式思维提示和逆向思维增强推理鲁棒性，有效缓解推理驱动的对抗性攻击。

> Despite significant efforts to align large language models with human values and ethical guidelines, these models remain susceptible to sophisticated jailbreak attacks that exploit their reasoning capabilities. Traditional safety mechanisms often focus on detecting explicit malicious intent, leaving deeper vulnerabilities unaddressed. In this work, we introduce a jailbreak technique, POATE (Polar Opposite query generation, Adversarial Template construction, and Elaboration), which leverages contrastive reasoning to elicit unethical responses. POATE generates prompts with semantically opposite intents and combines them with adversarial templates to subtly direct models toward producing harmful responses. We conduct extensive evaluations across six diverse language model families of varying parameter sizes, including LLaMA3, Gemma2, Phi3, and GPT-4, to demonstrate the robustness of the attack, achieving significantly higher attack success rates (~44%) compared to existing methods. We evaluate our proposed attack against seven safety defenses, revealing their limitations in addressing reasoning-based vulnerabilities. To counteract this, we propose a defense strategy that improves reasoning robustness through chain-of-thought prompting and reverse thinking, mitigating reasoning-driven adversarial exploits.

[Arxiv](https://arxiv.org/abs/2501.01872)