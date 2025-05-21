# 上下文推理器：利用强化学习促进推理能力，实现上下文感知的隐私与安全合规

发布时间：2025年05月20日

`LLM应用`

> Context Reasoner: Incentivizing Reasoning Capability for Contextualized Privacy and Safety Compliance via Reinforcement Learning

# 摘要

> 大型语言模型（LLMs）虽然能力出众，但其背后隐藏着不容忽视的安全与隐私风险。现有的防护措施往往顾此失彼，要么放弃情境推理能力，要么过度依赖模式匹配，导致效果有限。更糟糕的是，这些方法还忽视了既有的安全隐私标准，给法律合规埋下隐患。为解决这些问题，我们基于情境完整性（CI）理论，将安全隐私问题转化为情境化的合规问题。在CI框架下，我们让模型遵循三大核心标准：GDPR、欧盟《人工智能法案》和HIPAA。具体来说，我们采用强化学习（RL）技术，通过规则奖励机制，既提升模型的情境推理能力，又增强其对安全隐私规范的遵守。经过大量实验验证，我们的方法不仅将安全隐私基准的准确率提升了17.64%，还显著增强了模型的通用推理能力。以OpenThinker-7B为例，这款远超其基础模型Qwen2.5-7B-Instruct的强推理模型，在MMLU和LegalBench基准测试中，分别实现了2.05%和8.98%的准确率提升。

> While Large Language Models (LLMs) exhibit remarkable capabilities, they also introduce significant safety and privacy risks. Current mitigation strategies often fail to preserve contextual reasoning capabilities in risky scenarios. Instead, they rely heavily on sensitive pattern matching to protect LLMs, which limits the scope. Furthermore, they overlook established safety and privacy standards, leading to systemic risks for legal compliance. To address these gaps, we formulate safety and privacy issues into contextualized compliance problems following the Contextual Integrity (CI) theory. Under the CI framework, we align our model with three critical regulatory standards: GDPR, EU AI Act, and HIPAA. Specifically, we employ reinforcement learning (RL) with a rule-based reward to incentivize contextual reasoning capabilities while enhancing compliance with safety and privacy norms. Through extensive experiments, we demonstrate that our method not only significantly enhances legal compliance (achieving a +17.64% accuracy improvement in safety/privacy benchmarks) but also further improves general reasoning capability. For OpenThinker-7B, a strong reasoning model that significantly outperforms its base model Qwen2.5-7B-Instruct across diverse subjects, our method enhances its general reasoning capabilities, with +2.05% and +8.98% accuracy improvement on the MMLU and LegalBench benchmark, respectively.

[Arxiv](https://arxiv.org/abs/2505.14585)