# # 强化通用推理无需验证器

发布时间：2025年05月27日

`LLM理论` `人工智能`

> Reinforcing General Reasoning without Verifiers

# 摘要

> 近期，采用DeepSeek-R1-Zero风格的强化学习（RL）在可验证奖励下训练大型语言模型（LLMs）的范式转变，推动了代码和数学推理能力的显著提升。然而，这种方法的应用范围受限于可进行基于规则验证的任务，难以自然扩展到化学、医疗、工程、法律、生物、商业和经济等现实领域。当前实践中，通常借助额外的LLM作为验证器，但这带来了对强验证器模型的依赖、易受奖励欺骗的影响以及内存维护的负担。

为解决这些问题并扩展强化学习训练到通用推理领域，我们提出了一种无需验证器的方法——VeriFree。该方法绕过传统的答案验证环节，直接通过强化学习最大化生成参考答案的概率。实验结果表明，VeriFree不仅在计算需求和实际应用中具有显著优势，还在MMLU-Pro、GPQA、SuperGPQA和数学相关基准测试中表现优异，甚至超越了传统验证器方法。

此外，我们从多个角度深入分析了VeriFree：它不仅实现了策略与隐式验证器在同一模型中的优雅整合，还体现了变分优化方法的独特魅力。VeriFree的代码已开源，详情请访问https://github.com/sail-sg/VeriFree。

> The recent paradigm shift towards training large language models (LLMs) using DeepSeek-R1-Zero-style reinforcement learning (RL) on verifiable rewards has led to impressive advancements in code and mathematical reasoning. However, this methodology is limited to tasks where rule-based answer verification is possible and does not naturally extend to real-world domains such as chemistry, healthcare, engineering, law, biology, business, and economics. Current practical workarounds use an additional LLM as a model-based verifier; however, this introduces issues such as reliance on a strong verifier LLM, susceptibility to reward hacking, and the practical burden of maintaining the verifier model in memory during training. To address this and extend DeepSeek-R1-Zero-style training to general reasoning domains, we propose a verifier-free method (VeriFree) that bypasses answer verification and instead uses RL to directly maximize the probability of generating the reference answer. We compare VeriFree with verifier-based methods and demonstrate that, in addition to its significant practical benefits and reduced compute requirements, VeriFree matches and even surpasses verifier-based methods on extensive evaluations across MMLU-Pro, GPQA, SuperGPQA, and math-related benchmarks. Moreover, we provide insights into this method from multiple perspectives: as an elegant integration of training both the policy and implicit verifier in a unified model, and as a variational optimization approach. Code is available at https://github.com/sail-sg/VeriFree.

[Arxiv](https://arxiv.org/abs/2505.21493)