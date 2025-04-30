# 通过引用机制实现模型的鲁棒性：防御提示注入攻击的新思路——引用已执行指令

发布时间：2025年04月29日

`LLM应用`

> Robustness via Referencing: Defending against Prompt Injection Attacks by Referencing the Executed Instruction

# 摘要

> 大型语言模型（LLMs）在自然语言处理（NLP）领域表现卓越，但其强大的指令遵循能力也带来了安全隐患——易受提示注入攻击影响。这些攻击通过在数据内容中注入恶意指令，诱导LLMs偏离正常流程。现有防御手段多通过提示工程或微调来抑制模型执行恶意指令，但效果有限。我们的研究发现，虽然LLMs会响应各类指令，但它们能准确识别并引用原始提示内容。基于此，我们提出了一种创新防御方法：不再抑制，而是利用LLMs的指令遵循能力。通过让模型生成包含答案及其指令引用的响应，我们能有效筛选出合规回答。实验表明，该方法不仅超越传统基线，在某些场景下甚至将攻击成功率降至0%，同时对模型实用性影响微乎其微。

> Large language models (LLMs) have demonstrated impressive performance and have come to dominate the field of natural language processing (NLP) across various tasks. However, due to their strong instruction-following capabilities and inability to distinguish between instructions and data content, LLMs are vulnerable to prompt injection attacks. These attacks manipulate LLMs into deviating from the original input instructions and executing maliciously injected instructions within data content, such as web documents retrieved from search engines. Existing defense methods, including prompt-engineering and fine-tuning approaches, typically instruct models to follow the original input instructions while suppressing their tendencies to execute injected instructions. However, our experiments reveal that suppressing instruction-following tendencies is challenging. Through analyzing failure cases, we observe that although LLMs tend to respond to any recognized instructions, they are aware of which specific instructions they are executing and can correctly reference them within the original prompt. Motivated by these findings, we propose a novel defense method that leverages, rather than suppresses, the instruction-following abilities of LLMs. Our approach prompts LLMs to generate responses that include both answers and their corresponding instruction references. Based on these references, we filter out answers not associated with the original input instructions. Comprehensive experiments demonstrate that our method outperforms prompt-engineering baselines and achieves performance comparable to fine-tuning methods, reducing the attack success rate (ASR) to 0 percent in some scenarios. Moreover, our approach has minimal impact on overall utility.

[Arxiv](https://arxiv.org/abs/2504.20472)