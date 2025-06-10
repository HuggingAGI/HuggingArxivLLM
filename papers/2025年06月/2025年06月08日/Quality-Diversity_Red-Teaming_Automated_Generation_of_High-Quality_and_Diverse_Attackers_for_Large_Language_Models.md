# 质优多样的红队测试：自动化生成适用于大型语言模型的高质量多样化攻击者

发布时间：2025年06月08日

`LLM应用` `人工智能安全` `网络安全`

> Quality-Diversity Red-Teaming: Automated Generation of High-Quality and Diverse Attackers for Large Language Models

# 摘要

> 大型语言模型（LLMs）的安全性至关重要。红队测试作为一种系统性识别对抗提示的方法，已成为LLM安全评估的关键手段。在这一框架下，对抗提示的多样性对全面安全评估尤为关键。然而，我们发现传统红队测试方法存在两大局限：其一，常用简单的度量标准（如词频或句嵌入相似性）追求多样性，却难以捕捉攻击策略的实质变化；其二，单一攻击者模型的训练方式限制了对攻击风格和风险类别的覆盖范围。本文提出了一种全新框架——质量多样性红队测试（QDRT），旨在突破这些限制。通过行为条件化训练，QDRT实现了目标导向的多样性，并以开放式方式构建行为回放缓存。同时，它训练了多个专业攻击者，能够生成跨多种风格和风险类别的高质量攻击。实证评估表明，QDRT生成的攻击不仅更具多样性，而且在针对GPT-2、Llama-3、Gemma-2和Qwen2.5等广泛LLM目标时表现更优。这项研究通过提供一种系统化且有效的自动化红队测试方法，推动了LLM安全领域的进步，助力LLMs的责任化部署。

> Ensuring safety of large language models (LLMs) is important. Red teaming--a systematic approach to identifying adversarial prompts that elicit harmful responses from target LLMs--has emerged as a crucial safety evaluation method. Within this framework, the diversity of adversarial prompts is essential for comprehensive safety assessments. We find that previous approaches to red-teaming may suffer from two key limitations. First, they often pursue diversity through simplistic metrics like word frequency or sentence embedding similarity, which may not capture meaningful variation in attack strategies. Second, the common practice of training a single attacker model restricts coverage across potential attack styles and risk categories. This paper introduces Quality-Diversity Red-Teaming (QDRT), a new framework designed to address these limitations. QDRT achieves goal-driven diversity through behavior-conditioned training and implements a behavioral replay buffer in an open-ended manner. Additionally, it trains multiple specialized attackers capable of generating high-quality attacks across diverse styles and risk categories. Our empirical evaluation demonstrates that QDRT generates attacks that are both more diverse and more effective against a wide range of target LLMs, including GPT-2, Llama-3, Gemma-2, and Qwen2.5. This work advances the field of LLM safety by providing a systematic and effective approach to automated red-teaming, ultimately supporting the responsible deployment of LLMs.

[Arxiv](https://arxiv.org/abs/2506.07121)