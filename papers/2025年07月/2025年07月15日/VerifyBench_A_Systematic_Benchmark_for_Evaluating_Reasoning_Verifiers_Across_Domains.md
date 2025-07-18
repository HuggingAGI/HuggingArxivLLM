# VerifyBench: 跨领域推理验证器的系统性评估基准

发布时间：2025年07月15日

`LLM应用`

> VerifyBench: A Systematic Benchmark for Evaluating Reasoning Verifiers Across Domains

# 摘要

> 大型语言模型（LLMs）越来越依赖强化学习（RL）通过反馈来增强推理能力。然而，验证模型生成的响应与参考答案的一致性面临重大挑战，因为这些响应通常冗长、多样且微妙。基于规则的验证器在应对复杂性时力不从心，促使了基于模型的验证器的采用。然而，专用验证器缺乏灵活性，而通用LLM裁判则可能表现不一致。现有研究主要集中在构建更好的验证器上，然而，对不同类型的验证器在跨领域性能的系统性评估仍然不足，这严重制约了可验证奖励强化学习（RLVR）的可靠发展。为了解决这一问题，我们提出VerifyBench——一个跨领域的综合基准，用于系统性评估验证器。我们构建了涵盖数学、物理、化学和生物的4,000个专家级问题，每个问题都配备参考答案和多样化响应。评估的可靠性通过一个多学科专家团队进行的严格标注过程得到了保障。我们设计了一个四维实验框架，以在提取答案与完整响应、简短与长输出的综合条件下，全面比较专用验证器和通用LLM的性能边界。我们的评估揭示了验证器中的基本权衡：专用验证器在准确性方面处于领先地位，但在召回率方面存在缺陷；通用模型则表现出更强的包容性，但精确度不稳定。更重要的是，我们发现验证器对输入结构的高度敏感性和跨领域泛化的固有局限性，这为当前验证器技术的瓶颈提供了关键见解。

> Large language models (LLMs) increasingly rely on reinforcement learning (RL) to enhance their reasoning capabilities through feedback. A critical challenge is verifying the consistency of model-generated responses and reference answers, since these responses are often lengthy, diverse, and nuanced. Rule-based verifiers struggle with complexity, prompting the use of model-based verifiers. However, specialized verifiers lack flexibility, while general LLM judges can be inconsistent. Existing research primarily focuses on building better verifiers, yet a systematic evaluation of different types of verifiers' performance across domains remains lacking, severely constraining the reliable development of Reinforcement Learning with Verifiable Reward (RLVR). To address this, we propose VerifyBench--a cross-domain comprehensive benchmark for systematically evaluating verifiers. We construct 4,000 expert-level questions covering mathematics, physics, chemistry, and biology. Each question is equipped with reference answers and diverse responses. The reliability of the evaluation is ensured through a rigorous annotation process conducted by a multidisciplinary expert team. We design a four-dimensional experimental framework to comprehensively compare the performance boundaries of specialized verifiers and general LLMs under combined conditions of extracted answers vs. complete responses, and short vs. long outputs. Our evaluation uncovers fundamental trade-offs in verifiers: while specialized verifiers achieve leading accuracy, they exhibit deficiencies in recall; general models show stronger inclusivity but unstable precision. More importantly, we discover verifiers' high sensitivity to input structure and inherent limitations in cross-domain generalization, providing critical insights into the bottlenecks of current verifier technology.

[Arxiv](https://arxiv.org/abs/2507.09884)