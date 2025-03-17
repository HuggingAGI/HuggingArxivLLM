# # 深度对齐：通过渐进式回答解毒抵御越狱攻击

发布时间：2025年03月14日

`LLM理论` `模型安全`

> Align in Depth: Defending Jailbreak Attacks via Progressive Answer Detoxification

# 摘要

> 大型语言模型（LLMs）容易受到越狱攻击，这些攻击通过精心设计的提示来诱使模型生成有害内容。这些攻击利用了LLMs在生成过程中难以动态检测有害意图的弱点。传统的安全对齐方法由于计算预算有限，往往难以有效应对这些攻击。本文提出了一种名为DEEPALIGN的鲁棒防御框架，通过对LLMs进行微调，逐步净化生成内容，从而显著提升了计算预算和有害生成缓解效果。我们的方法采用了一种作用于隐藏状态的混合损失函数，直接提升LLMs在生成过程中对有害内容的内在感知能力。此外，我们通过为有害查询生成语义相关的安全回答重新定义了安全响应，从而提高了对表征突变攻击的鲁棒性。在多个LLMs上的评估结果表明，DEEPALIGN在防御六种不同类型的攻击方面达到了最先进的性能，与之前最先进的防御方法相比，攻击成功率降低了两个数量级，同时保持了模型的实用性。这项工作通过动态、上下文感知的缓解措施，解决了传统对齐方法的局限性，从而推进了LLM的安全性。

> Large Language Models (LLMs) are vulnerable to jailbreak attacks, which use crafted prompts to elicit toxic responses. These attacks exploit LLMs' difficulty in dynamically detecting harmful intents during the generation process. Traditional safety alignment methods, often relying on the initial few generation steps, are ineffective due to limited computational budget. This paper proposes DEEPALIGN, a robust defense framework that fine-tunes LLMs to progressively detoxify generated content, significantly improving both the computational budget and effectiveness of mitigating harmful generation. Our approach uses a hybrid loss function operating on hidden states to directly improve LLMs' inherent awareness of toxity during generation. Furthermore, we redefine safe responses by generating semantically relevant answers to harmful queries, thereby increasing robustness against representation-mutation attacks. Evaluations across multiple LLMs demonstrate state-of-the-art defense performance against six different attack types, reducing Attack Success Rates by up to two orders of magnitude compared to previous state-of-the-art defense while preserving utility. This work advances LLM safety by addressing limitations of conventional alignment through dynamic, context-aware mitigation.

[Arxiv](https://arxiv.org/abs/2503.11185)