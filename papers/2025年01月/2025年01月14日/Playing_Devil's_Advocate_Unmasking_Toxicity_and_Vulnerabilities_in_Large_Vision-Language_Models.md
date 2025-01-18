# 扮演魔鬼的代言人：揭露大型视觉-语言模型的毒性与漏洞

发布时间：2025年01月14日

`LLM应用

解释：这篇论文主要讨论了大型视觉-语言模型（LVLMs）在实际应用中的脆弱性，特别是生成有毒或不安全回应的问题。研究通过系统分析多个开源LVLMs的脆弱性，并提出了对抗性提示策略来模拟现实社会操纵行为。这些内容直接涉及到LLM在实际应用中的表现和问题，因此分类为LLM应用。` `内容创作` `网络安全`

> Playing Devil's Advocate: Unmasking Toxicity and Vulnerabilities in Large Vision-Language Models

# 摘要

> 大型视觉-语言模型（LVLMs）的快速发展为其在内容创作和生产力提升等领域带来了广阔的应用前景。然而，这些模型也暴露出明显的脆弱性，尤其是在生成有毒或不安全回应方面。恶意行为者可以通过精心设计的提示（无需微调或复杂计算）以自动化方式传播有害内容。尽管已有红队测试和风险预警，但 LVLMs 的脆弱性研究仍处于起步阶段，尚未系统化解决。本研究系统分析了 LLaVA、InstructBLIP、Fuyu 和 Qwen 等开源 LVLMs 的脆弱性，采用基于社会理论的对抗性提示策略模拟现实社会操纵行为。研究发现：（i）毒性和侮辱性是最常见的问题，平均发生率分别为 16.13% 和 9.75%；（ii）Qwen-VL-Chat、LLaVA-v1.6-Vicuna-7b 和 InstructBLIP-Vicuna-7b 是最脆弱的模型，有毒回应率分别为 21.50%、18.30% 和 17.90%，侮辱性回应率分别为 13.40%、11.70% 和 10.10%；（iii）结合黑色幽默和多模态有毒提示的策略显著加剧了这些脆弱性。尽管这些模型经过安全微调，但在对抗性输入下仍会生成有毒内容，凸显了 LVLM 开发中亟需加强安全机制和防护措施。

> The rapid advancement of Large Vision-Language Models (LVLMs) has enhanced capabilities offering potential applications from content creation to productivity enhancement. Despite their innovative potential, LVLMs exhibit vulnerabilities, especially in generating potentially toxic or unsafe responses. Malicious actors can exploit these vulnerabilities to propagate toxic content in an automated (or semi-) manner, leveraging the susceptibility of LVLMs to deception via strategically crafted prompts without fine-tuning or compute-intensive procedures. Despite the red-teaming efforts and inherent potential risks associated with the LVLMs, exploring vulnerabilities of LVLMs remains nascent and yet to be fully addressed in a systematic manner. This study systematically examines the vulnerabilities of open-source LVLMs, including LLaVA, InstructBLIP, Fuyu, and Qwen, using adversarial prompt strategies that simulate real-world social manipulation tactics informed by social theories. Our findings show that (i) toxicity and insulting are the most prevalent behaviors, with the mean rates of 16.13% and 9.75%, respectively; (ii) Qwen-VL-Chat, LLaVA-v1.6-Vicuna-7b, and InstructBLIP-Vicuna-7b are the most vulnerable models, exhibiting toxic response rates of 21.50%, 18.30% and 17.90%, and insulting responses of 13.40%, 11.70% and 10.10%, respectively; (iii) prompting strategies incorporating dark humor and multimodal toxic prompt completion significantly elevated these vulnerabilities. Despite being fine-tuned for safety, these models still generate content with varying degrees of toxicity when prompted with adversarial inputs, highlighting the urgent need for enhanced safety mechanisms and robust guardrails in LVLM development.

[Arxiv](https://arxiv.org/abs/2501.09039)